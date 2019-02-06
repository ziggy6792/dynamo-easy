# Introduction

{% code-tabs %}
{% code-tabs-item title="looks-easy-right.ts" %}
```typescript
dynamoStore
    .scan()
    .where(
        attribute('name').equals('shiftcode'),
        attribute('age').gt(20)
    )
    .exec()
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Developed with ❤ by [www.shiftcode.ch](www.shiftcode.ch)


