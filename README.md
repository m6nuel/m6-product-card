# m6-product-card

Este es un paquete de pruebas de NPM


### Jesus Delgado

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'm6-product-card';
```


```
<ProductCard 
    product={ product }
    initialValues={{
        count: 5,
        maxCount: 10
    }}
>
    {
        ( { reset, count, maxCount, increaseBy, isMaxCountReached } ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```