---
title: 'test'
date: '2022-01-24'
---

# test

## test

### test

- test
- test
- test

1. test
1. test
1. test

```ts
import { parseISO, format } from 'date-fns';

export default function Date({ dateString }: { dateString: string }) {
  const date = parseISO(dateString);
  return <time dateTime={dateString}>{format(date, 'LLLL d, yyyy')}</time>;
}
```
