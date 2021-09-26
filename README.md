# spring-boot-restAPI-app

@RequestMapping has several specialized convenience annotations:

>* @GetMapping: Retrieval of data is handled by this method
>* @PostMapping: To create resources, an HTTP POST method is the preferred option.
>* @PutMapping: used to update existing resources with known URIs.
>* @PatchMapping: used to request a set of modifications in the request entity to be applied for the resource recognized by the Request-URI
>* @DeleteMapping: To delete a resource, we use an HTTP DELETE request.


Use following http commands to test the application: (note: I used httpie, you can use postman as well)
> getCoffees(): http  :8080/coffees/
> 
> getCoffeeById(): http  :8080/coffees/f87b3d87-f5a7-4d0f-918a-6d590b538906
> 
> postCoffee(): http  :8080/coffees < sample1.json 
> 
> putCoffee(): http PUT :8080/coffees/123 < sample2.json
> 
> deleteCoffee(): http DELETE :8080/coffees/123

