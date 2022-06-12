# Golang Up and Running

## Installation Steps

1. Download Golang installation file from https://go.dev/doc/install
2. Download IDE (VSCODE) from https://code.visualstudio.com/
3. Download golang plugin from https://marketplace.visualstudio.com/items?itemName=golang.Go

## GO Concepts

1. Environment variables

   - GOPATH - custom location of your projects
   - GOROOT - installation directory or location of your executables

2. Go package
   - Package name can be either folder name or `main`
   - Multiple files in a single folder can't declare multiple pacakges
3. Go encapsulation
   - Anything starts with uppercase letter is public
   - Anything starts with lowercase letter is private

Go always runs the `main` function on the `main` package

## Go syntax

1. Function definition

```
func function_name(a int, b string, c bool) return_type {

}
```

- func - keyword reserved
- function_name - name of the functions
- arguments - name and type of each arguments
- return_type - the type that the function returns

2. Variable declaration

- Long way declaration

  ```
      var variable_name type
  ```

  - var - reserved keyword
  - variable_name - custom variable name
  - type - data type of the variable (int, float, bool, character, string, double)

- Short way declaration
  ```
      variable_name := initial_value
  ```

3. Control Statement

```
    if condition {

    } else if condition {

    } else {

    }

```
