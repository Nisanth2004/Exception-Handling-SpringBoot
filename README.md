# Exception-Handling-SpringBoot

    <groupId>org.springframework.boot </groupId>
    <artifactId>spring-boot-starter-validation</artifactId>

# Annoations
    @ExceptionHandler(MethodArgumentNotValidException.class)
    @NotBlank
    @ResponseStatus(HttpStatus.BAD_REQUEST)
    @RestControllerAdvice

