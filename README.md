# Make the bug

- rename ./modules/user/_index.ts to ./modules/user/index.ts
- run `npm run postinstall`
- check ./modules/user/components/DeepComponent.vue, and The bug should happen

# Revert the bug

- rename ./modules/user/index.ts to ./modules/user/_index.ts
- run `npm run postinstall`
- The bug should not happen
