# Contributing to the codebase
As a developer we encounter different styles of coding, be it from our previous works, during our learning phases or just an acquired style that we prefer. This won't be much of a problem if we are working alone, but since this is a company project, somebody at some point will have to pick up your code, or you may pick up somebody else's code.

This guide aims to set a standard style so that we would have a more cohesive codebase, following a set of coding standards that maximizes our productivity by making both writing and reading codes easy.

## Coding Styles

### PHP/ Laravel

1. Use [PHPDoc DocBlocks](https://docs.phpdoc.org/3.0/guide/getting-started/what-is-a-docblock.html) on functions, variables, classes, interfaces, etc. This will allow us to easily get a summary of the code does without spending too much time reading the code. This also enables intellisense when referring to another code, and also the phpdoc itself that would automatically generate the documentation reference for the project.

1. For the sake of organization and cohesiveness, when using PhpDoc DocBlocks refer to this template:
```php
/**
 * Brief Summary of the code
 * 
 * Long description of the code, optional. Use when the code is complex.
 * 
 * @param string $name Brief description of the parameter
 * @param string $middleName (Optional) Do this for optional parameters
 * @param array<string, int> $contactNumbers Use this for associative arrays with string as keys and int for values
 * 
 * @return Object Brief summary of the return object, optional.
 * 
 * @throws Exception Brief summary what triggers this exception to be thrown
 * 
 * @route GET api/v1/user This is optional use only for controller functions. Describes the HTTP method and its route
 */
public function createUser(string $name, string $middleName = '', array $contactNumbers): Object {
    // Code here
}
```

> For more information check:
> 
> - [What is a DocBlock](https://docs.phpdoc.org/3.0/guide/getting-started/what-is-a-docblock.html)
> - [More on DocBlocks](https://docs.phpdoc.org/3.0/guide/guides/docblocks.html)

3. //

1. //

### Javascript / Typescript

1. //

## Git Repository
Structuring your code into bitesize commits and branches for clearer distinction on the git history

1. Divide your tasks into branches
1. //
