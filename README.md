# template-expression-operators

In Angular, template expression operators are used within curly braces ({{ }}) to perform various operations and manipulations on values in the template. These operators allow you to dynamically compute values, perform logical operations, iterate over collections, and more.

Here are some commonly used template expression operators in Angular:

## Arithmetic Operators:

+: Addition
-: Subtraction
*: Multiplication
/: Division
%: Modulus
Example:
```typescript
<p>{{ 10 + 5 }}</p> <!-- Output: 15 -->
<p>{{ 10 * 2 }}</p> <!-- Output: 20 -->
<p>{{ 10 % 3 }}</p> <!-- Output: 1 -->
```

## Comparison Operators:

==: Equality
!=: Inequality
<: Less than
>: Greater than
<=: Less than or equal to
>=: Greater than or equal to
Example:
```typescript
<p>{{ 5 == 5 }}</p> <!-- Output: true -->
<p>{{ 10 > 5 }}</p> <!-- Output: true -->
```

## Logical Operators:

&&: Logical AND
||: Logical OR
!: Logical NOT
Example:
```typescript
<p>{{ true && false }}</p> <!-- Output: false -->
<p>{{ true || false }}</p> <!-- Output: true -->
<p>{{ !true }}</p> <!-- Output: false -->
```

## Ternary Operator:
The ternary operator (condition ? expression1 : expression2) allows you to make decisions based on a condition.

Example:
```typescript
<p>{{ isLoggedIn ? 'Welcome!' : 'Please log in.' }}</p>
```

## Safe Navigation Operator (Elvis Operator):
The safe navigation operator (?.) allows you to handle null or undefined values without causing errors.

Example:
```typescript
<p>{{ user?.name }}</p>
```

These are just a few examples of the template expression operators available in Angular. You can combine these operators to create more complex expressions and perform dynamic computations in your Angular templates.
