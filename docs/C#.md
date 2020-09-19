---
layout: default
title: C#
nav_order: 5
---
# C#
* Value types vs Reference types
* Covariance and Contravariance  
[Covariance and Contravariance in Generics](https://docs.microsoft.com/en-us/dotnet/standard/generics/covariance-and-contravariance){:target="_blank"}  
[Covariance and Contravariance (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/covariance-contravariance/){:target="_blank"}

## [C# 6](https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-6){:target="_blank"}

### Read-only auto-properties
```c# 
public string FirstName { get; }
```

### Auto-property initializers
```csharp
public ICollection<double> Grades { get; } = new List<double>();
```

### Expression-bodied function members
```c# 
public override string ToString() => $"{LastName}, {FirstName}";
```

### Null-conditional operators
```c#
var first = person?.FirstName;
```

### String interpolation
```c#
public string FullName => $"{FirstName} {LastName}";
```

### Exception filters
```c#
try
{
} 
catch (System.Net.Http.HttpRequestException e) when (e.Message.Contains("301"))
{
}
```

### The nameof expression
```c#
public string LastName
{
}
nameof(LastName)
```

### Await in Catch and Finally blocks

### Initialize associative collections using indexers
```c#
[404] = "Page not Found",
[302] = "Page moved, but left a forwarding address.",
[500] = "The web server can't come out to play today."
```

## C# 7.0
## C# 8.0 
.NET Core 3.x and .NET Standard 2.1.
### Default interface methods
### Nullable reference types