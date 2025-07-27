
* ignore GEMINI.md


## Project Structure

*   

    *   reusable libraries 

        ```
        ./source/
        ```

    *   samples   

        ```
        ./samples/
        ```

    *   tests   

        ```
        ./tests/
        ```

        *   unit-tests   

            ```
            ./tests/unit-tests/
            ```

        *   benchmark-tests   

            ```
            ./tests/benchmark-tests/
            ```

## Style

*   use Allman style

    ```csharp
    ```
    
*   prefer target-type `new` over 

*   prefer collection exporessions over collection initializers

    ```csharp
    ```

*   braces for control strucutres

## Performance

*   strings

    1.  use `Cysharp.ZString` instead of `System.StringBuilder`

*   order of precedence of libraries to use for formatting (serialization/deserialization)

    *   JSON

        1.  `SpanJSON`

        2.  `System.Text.Json`

    *   XML 

        1.  

    *   CSV


