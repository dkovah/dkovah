```typescript
const alive = async (shenanigans: EventEmitter) => !await new Promise(resolve => shenanigans.once("finished", resolve));
```
