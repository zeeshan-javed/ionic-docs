```tsx
import React from 'react';
import { IonContent, IonRange } from '@ionic/react';

import './main.css';

function Example() {
  return (
    <IonContent className="ion-padding">
      <IonRange min={0} max={10} value={5} pin={true} ticks={true} snaps={true}></IonRange>
    </IonContent>
  );
}

export default Example;
```
