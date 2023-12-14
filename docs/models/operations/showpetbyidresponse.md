# ShowPetByIdResponse


## Fields

| Field                                                   | Type                                                    | Required                                                | Description                                             |
| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| `contentType`                                           | *string*                                                | :heavy_check_mark:                                      | HTTP response content type for this operation           |
| `error`                                                 | [components.ErrorT](../../models/components/errort.md)  | :heavy_minus_sign:                                      | unexpected error                                        |
| `pet`                                                   | [components.Pet](../../models/components/pet.md)        | :heavy_minus_sign:                                      | Expected response to a valid request                    |
| `statusCode`                                            | *number*                                                | :heavy_check_mark:                                      | HTTP response status code for this operation            |
| `rawResponse`                                           | [AxiosResponse](https://axios-http.com/docs/res_schema) | :heavy_check_mark:                                      | Raw HTTP response; suitable for custom response parsing |