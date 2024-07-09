# Validation Patterns

This repository contains a collection of regular expression patterns for validating various types of input data. These patterns can be used in web forms, APIs, or any other context where input validation is necessary.

## Patterns

Below is a list of the included validation patterns along with their descriptions:

1. **Email Pattern**
   - **Description**: Validates email addresses.
   - **Pattern**: `^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\\.[a-zA-Z]{2,}$`
   - **Example**: `example@example.com`

2. **Password Pattern**
   - **Description**: Validates passwords with at least one digit, one lowercase letter, one uppercase letter, and a minimum length of 8 characters.
   - **Pattern**: `(?=.*\\d)(?=.*[a-z])(?=.*[A-Z]).{8,}`
   - **Example**: `Password123`

3. **First Name Pattern**
   - **Description**: Validates first names containing only alphabetic characters.
   - **Pattern**: `^[A-Za-z]+$`
   - **Example**: `John`

4. **Last Name Pattern**
   - **Description**: Validates last names containing only alphabetic characters.
   - **Pattern**: `^[A-Za-z]+$`
   - **Example**: `Doe`

5. **Phone Number Pattern**
   - **Description**: Validates phone numbers in various formats.
   - **Pattern**: `^\\+?\\d{1,3}?[-.\\s]?\\(?\\d{1,4}\\)?[-.\\s]?\\d{1,4}[-.\\s]?\\d{1,4}[-.\\s]?\\d{1,4}$`
   - **Example**: `+1-800-555-5555`

6. **Address Pattern**
   - **Description**: Validates addresses containing alphanumeric characters, spaces, periods, commas, and hash symbols.
   - **Pattern**: `^[A-Za-z0-9\\s.,#]+$`
   - **Example**: `123 Main St., Apt #4`

7. **Website Pattern**
   - **Description**: Validates website URLs with HTTP or HTTPS protocols.
   - **Pattern**: `^(https?:\\/\\/)?([\\da-z.-]+)\\.([a-z.]{2,6})([\\/\\w .-]*)*\\/?$`
   - **Example**: `https://www.example.com`

8. **Date Pattern**
   - **Description**: Validates dates in the MM/DD/YYYY format.
   - **Pattern**: `^(0[1-9]|1[0-2])\\/(0[1-9]|1\\d|2[0-8])\\/(19|20)\\d{2}$`
   - **Example**: `12/31/2020`

9. **Username Pattern**
   - **Description**: Validates usernames with alphanumeric characters, underscores, and hyphens, with a minimum length of 4 and a maximum length of 16 characters.
   - **Pattern**: `^[a-zA-Z0-9_-]{4,16}$`
   - **Example**: `user_name`

10. **SSN Pattern**
    - **Description**: Validates social security numbers in the XXX-XX-XXXX format.
    - **Pattern**: `^\\d{3}-\\d{2}-\\d{4}$`
    - **Example**: `123-45-6789`

11. **Card Number Pattern**
    - **Description**: Validates credit card numbers using various card types.
    - **Pattern**: `^(?:4[0-9]{12}(?:(?:[0-9]{3})?)?|(?:5[1-5][0-9]{14})|(?:6(?:011|5[0-9]{2}))|(?:3[47][0-9]{13})|(?:3(?:0[0-8]|9)[0-9]{11}))$`
    - **Example**: `4111111111111111`

12. **CVV Pattern**
    - **Description**: Validates CVV (Card Verification Value) codes with a length of 3 or 4 digits.
    - **Pattern**: `^\\d{3,4}$`
    - **Example**: `123`

13. **IP Address Pattern**
    - **Description**: Validates IP addresses in the standard dotted-decimal notation.
    - **Pattern**: `^(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)$`
    - **Example**: `192.168.1.1`

14. **MAC Address Pattern**
    - **Description**: Validates MAC addresses in the standard colon-separated hexadecimal notation.
    - **Pattern**: `^([0-9A-Fa-f]{2}[:-]){5}([0-9A-Fa-f]{2})$`
    - **Example**: `00:1A:2B:3C:4D:5E`

## Usage

You can use these patterns in your project for input validation. For example, in JavaScript, you can use the `RegExp` object to create a regex pattern and test it against a string:

```javascript
const emailPattern = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
const email = "example@example.com";
console.log(emailPattern.test(email)); // true
```
## Authors

- [@Pankaj Goyal](https://github.com/Beginnerourwebsite/inputPattern.git)
- [@Email](mailto:pankajdesktop23@gmail.com)


## Deployment

To deploy this project run

```bash
  fetch("https://beginnerourwebsite.github.io/inputPattern/PatternObject.json")
  .then(function(res){
      return res.json()
  })
  .then(function(result){
       console.log(result)
  })
```


## 🚀 About Me
I'm a full stack developer...
We can create full stack website
on Node JS, MongoDB, MySQL, React JS, JS, CSS and HTML




## 🛠 Skills
Node JS, MongoDB, MySQL, React JS, JS, CSS and HTML...

