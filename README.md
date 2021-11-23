# NS-Product-card

Este es un paquete de pruebas de despliegue en NPM

### Natalia Silva

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'ns-product-card'


    <ProductCard
        product={product}
        initialValues={{
            count: 4,
            maxCount: 10
        }}
    >
        {
         ({reset, isMaxCountReached, increaseBy,  count }) => (
                <>
                    <ProductImage />
                    <ProductTitle />
                    <ProductButtons />
                </>
         )
        }

            </ProductCard>


```
