# UI components

Copy the `src/components/ui/` directory into your Next.js project.

Available exports:
- `Button` — variants: `primary`, `secondary`, `ghost`
- `Card`
- `Input`
- `Label`
- `Dialog` — controlled with `open` and `onClose`

Tailwind CSS must already be configured in the project. No additional UI dependency is required.

Example imports:
```tsx
import { Button } from "@/components/ui/button";
import { Card } from "@/components/ui/card";
import { Input } from "@/components/ui/input";
import { Label } from "@/components/ui/label";
import { Dialog } from "@/components/ui/dialog";
```
