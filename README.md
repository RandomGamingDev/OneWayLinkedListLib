# OneWayLinkedListLib
A simple one way linked list that stores the head, tail and length of the list

This library was created, not only for education purposes, but to be a fast, effiecient and easy to use one way linked list library, which are perfect for things like ECS. 

In case some of you are wondering why you would use this over std::list, just remember that std::list is a doubly linked list, which means that's it's storing an extra pointer, which is oftentimes uneeded and wasteful due to a lot of applications not needing this extra pointer. Although it might seem small at first, the more elements that you have to handle in your list the more memory is wasted. Plus, this library is a lot simpler to understand and edit for all your needs!
