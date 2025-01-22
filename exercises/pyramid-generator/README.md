# Pyramid Generator

This exercise generates a pyramid pattern using a specified character and number of levels.

## Usage

### Example

#### Input:

- **Character**: `!`
- **Count**: `10`

#### Output:

```
         !
        !!!
       !!!!!
      !!!!!!!
     !!!!!!!!!
    !!!!!!!!!!!
   !!!!!!!!!!!!!
  !!!!!!!!!!!!!!!
 !!!!!!!!!!!!!!!!!
!!!!!!!!!!!!!!!!!!!
```

## How It Works

1. **Padding**: Each row is centered using spaces to align the pyramid.
2. **Building Rows**: Rows are generated and optionally inverted.
3. **Output**: Rows are concatenated and printed as a pyramid.

## Code Highlights

- **`padRow`**: Generates a padded row.
- **Loop**: Iterates through the levels to build rows.
- **Inversion**: Allows creating inverted pyramids (not enabled in this example).

---

Happy coding! 🚀
