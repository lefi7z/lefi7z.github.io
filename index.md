Moritz Koenemann
===================

Physicist and Software Developer
-------------------

Austr. 44 / Rum / Innsbruck

"Man muss die Dinge so einfach wie möglich machen. Aber nicht einfacher!"  
(A. Einstein)

```c
// return the count of children of `head`
int count(node_t* head)
{
    if (head == NULL)
        return 0;

    return 1 + count(head->left) + count(head->right);
}
```
