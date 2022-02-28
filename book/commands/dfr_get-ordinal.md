---
title: dfr get-ordinal
layout: command
version: 0.59.0
---

Gets ordinal from date

## Signature

```> dfr get-ordinal ```

## Examples

Returns ordinal from a date
```shell
> let dt = ('2020-08-04T16:39:18+00:00' | into datetime -z 'UTC');
    let df = ([$dt $dt] | dfr to-df);
    $df | dfr get-ordinal
```