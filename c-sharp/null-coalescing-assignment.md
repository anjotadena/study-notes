# Null-Coalescing Assignment ?=
- This operator was intruduced in C# 8
- This works similar to the Null-Coalescing operator(??)

## Difference
- Null-Coalescing Assignment assigns the value of the left-operand in case the left-operand was null.

### Example:
`c#
// Traditional Way
BlogModel? blog = await GetBlogById(1);

if (blog is null)
{
  blog = new BlogModel
  {
    Id = 1,
    Name = "Coding"
  }
}

// Null-Coalescing Assignment
BlogModel? blog = await GetBlogById(1);

blog ??= new BlogModel
{
    Id = 1,
    Name = "Coding"
}

`
