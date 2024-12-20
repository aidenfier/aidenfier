```javascript
"use strict";

import { UserGeneratorSystem as User } from "ID-CARD";

const userGeneratorSystem = async () => {
  return await User({
    status: 200,
    data: {
      displayName: "Amin",
      knownAs: "Aiden Fier",
      nickName: "Crawler",
      birthday: "01 June",
      jobData: {
        jobArea: [
          "NodeJS",
          "ExpressJS",
          "JS",
          "RegEX",
          "Canvas 2D Rendering",
          "PHP",
        ],
        jobType: "Senior Developer",
      },
    },
  });
};

export default userGeneratorSystem;
```
