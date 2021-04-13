# Journal Day 1 - Week 11

## Daily Journal Questions

1. What does Inheritance accomplish for us in C#?

    Inheritence does 2 things. The first is it allows you use to reuse (or share) code between two classes. The second is it allows you to imprint identity into a class.

2. How does Member inheritance work in C#? Does a class inherit all members of the base class?

    Member inheritence allows a class to inherit, or adopt, all of the members from another class. A class can only inherit members that are set to public and protected, but not private.

3. How does accessibility affect inheritance?

    Private members aren't visible from child classes. Protected members are visible ONLY in child classes. Internal members are visible in derived classes located in the same assembly as the parent class.
