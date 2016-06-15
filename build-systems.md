|                     | Dynamic dependencies | Shared build | Supports non-determinism | Benefits from determinism | Stores all intermediates |
|:-------------------:|:--------------------:|:------------:|:------------------------:|:-------------------------:|:------------------------:|
| Nick's build system |          No          |      Yes     |            Yes           |            Yes            |            No            |
| Shake               |          Yes         |      No      |            Yes           |            Yes            |            Yes           |
| Buck                |          No          |      Yes     |            No            |         Yes, a lot        |            Yes           |
| Excel               |          Yes         |      No      |            Yes           |            Yes            |            Yes           |
| Make                |          No          |      No      |            Yes           |             No            |            Yes           |
