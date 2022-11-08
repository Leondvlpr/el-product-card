# EL-product-card

Este es un paquete de pruebas de despliegue en NPM 

### Esteban leon

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'el-product-card'
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 4,
        maxCount: 10
    }}
>
    {
        ({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>

```
