
# EX 41 C program to write a function to find the peek of stack using array.
## DATE:
## AIM:
To write a function to find the peek of stack using array.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a function to find the peek of stack using array. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.  

## Program:
```
int stack[100],top; 
void peek() 
{ 
printf("%d",stack[top]); 
} 
```

## Output:
![image](https://github.com/user-attachments/assets/e6990a19-fb3b-459d-b7cb-ed4c69b331cf)


## Result:
Thus the program was executed and the output was verified successfully.

# EX 42 C program to write a fuctions to perform push,pop,display,peek in stack using array.
## DATE:
## AIM:
To write a fuctions to perform push,pop,display,peek in stack using array.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to perform push,pop,display,peek in stack using array. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.

## Program:
```
int stack[100]; 
int size=3,top=-1,i; 
void push (float data) 
{ 
if(top==size-1) 
{ 
printf("stack is full\n"); 
} 
else{ 
top=top+1; 
stack[top]=data;} 
} void display(){ 
for(i=top; i>=0; i--){ 
printf("%d ",stack[i]); 
} 
if(top==-1) 
{ 
printf("stack is empty\n"); 
}
Void pop() 
{ 
if(top==-1) 
{ 
printf("stack is empty\n"); 
} 
else{ 
top=top-1; 
} 
} 
void peek() 
{ 
printf("%d ",stack[top]); 
} 
```

## Output:
![image](https://github.com/user-attachments/assets/d2596242-eca9-45e5-81c0-e3d4f5d9c88a)


## Result:
Thus the program was executed and the output was verified successfully.

# EX 43 C program to Write a function to display queue elements using array.
## DATE:
## AIM:
To Write a function to display queue elements using array.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a function to display queue elements using array. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.

## Program:
```
float queue[50]; 
int rear=-1,front=-1,i; 
void display() 
{ 
if(front==-1||front>rear) 
printf("No elements to display\n"); 
else 
{ 
for(i=front;i<=rear;i++) 
printf("%.1f\n",queue[i]); 
} 
 
} 
void display() 
{ 
if(front==-1||front>rear) 
{  
printf("No elements to display\n"); 
else 
{ 
for(i=front;i<=rear;i++)
```

## Output:
![image](https://github.com/user-attachments/assets/6b1348f5-936d-4b8f-9478-3a848914c08c)


## Result:
Thus the program was executed and the output was verified successfully.
# EX 44 C functions to perform enqueue, dequeue, display, peek in Queue using Array.
## DATE: 
## AIM:
To write a C Write a functions to perform enqueue, dequeue, display, peek in Queue using Array.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to perform enqueue,dequeue ,display,peek in Queue using array. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End   

## Program:
```
char queue[50]; 
int size=10,front,rear,i; 
void enqueue(char data) 
{ 
if(rear<size) 
{ 
if(front==-1) 
{ 
front=0; 
} 
rear=rear+1; 
queue[rear]=data; 
} 
{ 
printf("%c\n",queue[i]); 
} 
} 
void dequeue() 
{  
if(front==-1||front>rear) 
{ 
printf("Queue Underflow\n"); 
} 
else 
{ 
front=front+1; 
} 
 
} 
void peek() 
{ 
printf("%c\n",queue[front]); 
 
} 
 
}
```

## Output:
![image](https://github.com/user-attachments/assets/3c69a98a-cbb9-4608-b259-f8cb31a3a653)


## Result:
Thus the program was executed and the output was verified successfully.# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
## DATE:
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to traverse the linked list and display it in the following format. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End

## Program:
```
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void display() 
{ 
struct Node *temp; 
temp=head; 
while(temp!=NULL) 
{ 
printf("%c\n",temp->data); 
temp=temp->next; 
} 
 
} 
```

## Output:
![image](https://github.com/user-attachments/assets/b402ce73-b0c8-4b2c-9fe0-ddd383f0a3bb)



## Result:
Thus the program was executed and the output was verified successfully.
