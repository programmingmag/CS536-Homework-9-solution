# CS536-Homework-9-solution

Download Here: [CS536 Homework 9 solution](https://jarviscodinghub.com/assignment/cs536-homework-9-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1
Generate the MIPS code for the following function:
int doubleSum(int a, int b) {
b = a + b;
return b * 2;
}
Make sure that your function saves the return address and control link on the stack. You may choose to compute
intermediate values on the stack (as discussed in class) or you may choose to use registers. List any conventions
that you are assuming in your function (i.e. what is the offset or register where parameters are passed? What
register or slot do you place return values?)
Question 2
Consider the following block of MIPS code:
.text
main:
li $t0 2
li $t1 4
addu $t0 $t1 $t0
sw $t0 ($sp)
sw $t1 4($sp)
li $t2 8
subu $sp $sp $t2
lw $t3 4($sp)
lw $t0 8($sp)
li $ra 0x0
jr $ra
List the values in each of the following registers immediately after the jr instruction:
$t0
$t1
$t2
$t3
$ra
If any value is undefined by the function put undefined as the value.

