#include <stdio.h>
#include <stdlib.h>

struct mode{
int data;
struct node* prev;
struct node* next;
};
struct node* head;

void append(){
int item;
struct node* ptr;
ptr =(struct node*) malloc (size of(struct node));
printf("enter node data:");
scanf("%d", & item);
if(ptr == null){
printf("over low");
}else{
if(head == null){
ptr->next = null;
ptr->prev =null;
ptr->data = item;
head = ptr;
}else{
ptr->data = item;
ptr->prev = null;
ptr->next = head;
head-> prev = ptr;
head = ptr;
}
    printf("\nNode INSERTED\n");
  }
}
 
