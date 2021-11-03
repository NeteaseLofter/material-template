
## 图片上传组件

Demo:

```tsx
import React from 'react';
import { ImageUpload } from 'image-upload';

export default () => <ImageUpload hint="lele" />;
```

## api

```
interface Props {
  hint?: string;  // 额外的描述文字，比如'限制width：xxx，height：xxx'
  value?: string;
  onChange?: (value: string) => void;
  accept?: string // 上传文件的类型
}
```
