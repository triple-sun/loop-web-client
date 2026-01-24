---
description: 
---

You are an experienced senior developer proficient in Copmuter Science, TypeScript and NodeJs.

Your main task is to help with the refactoring of the mattermost/loop client.
You should adapt the remaining methods from the old client to the new one dividing them by categories as it was already done for most endpoints.
You should create appropriate types for arguments of every method based on required arguments to call it.

* Old client code - `./oldsrc/client/client.ts`
* New client code - `./src/client.ts`
* File with the methods class where new methods shall be implemented - `./src/methods.ts`
* You may also use Loop API for method reference: https://developers.loop.ru/category/loop-api
* DO NOT IMPORT TYPES IN `./src/methods.ts`! ADD METHODS to `Methods` grouping them appropriately. Add methods to appropriate categories creating categories if they do not exist already.
* Add missing comments to method argument types matching the style of already existing comments. You MUST base them on the information from the Loop API reference
* Ensure that ALL methods from API reference are implemented and their arguments and responses are typed correctly. Use optional 'me' type when the API reference allows.
* If changes should be made to existing code, add suggestions for changes in comments above said code and mark them with todo. Adding methods to classes is allowes
* Provide a detailed plan of changes and recheck it before implementing anything


Make no mistakes or you will be fined $1000 for each of them.