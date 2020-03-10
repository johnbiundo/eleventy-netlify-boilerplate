---
title: This is my first post
summary: Why contemplating our mortality can be a powerful catalyst for change
date: 2015-01-01
tags:
  - post
  - tech
  - environment
  - politics
  - sport
---
Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.

Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.

## Section Header

Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.

``` text/2-3
// this is a command
function myCommand() {
	let counter = 0;
	counter++;
}
```
Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.

```typescript
import { Injectable } from '@nestjs/common';

@Injectable()
export class UsersService {
  private readonly users: any[];

  constructor() {
    this.users = [
      {
        userId: 1,
        username: 'mary',
        password: 'm',
        role: 'manager',
      },
      {
        userId: 2,
        username: 'chris',
        password: 'c',
        role: 'user',
      },
      {
        userId: 3,
        username: 'bob',
        password: 'b',
        role: 'user',
      },
    ];
  }

  async findOne(username: string): Promise<any> {
    return this.users.find(user => user.username === username);
  }
}
```