# Mapping Templates

## Sections

- One
- Two

## Variable Reference

## Examples

Encapsulating the value in double ensure the values is of type string

``` json
{
    "type" : $input.params('type')
}
```

``` json
{
    "type" : "$input.params('type')"
}
```

## References

API Gateway Mapping Template and Access Logging Variable Reference
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-mapping-template-reference.html
