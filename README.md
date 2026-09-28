# React DLS

Shared React components for the applications in this workspace.

## Components

### Button

```tsx
import { Button } from '@mehdifadaei-irn/react-dls'

export function Example() {
  return <Button variant="primary">Save changes</Button>
}
```

Available variants are `primary`, `secondary`, and `danger`.

## Tailwind requirement

This library uses Tailwind utility classes. Each consuming application must add this library's `src` directory to its Tailwind v3 `content` array. The application—not this library—compiles the final Tailwind CSS.
