STJC-PRODUCT-CARD

Este es un paquete de prueb ade despliege en npm

### Adrian stiven jimenez cardenas

```
import {ProductImage, ProductTitle, ProductButtons} from stijc-product-card
```

```
        <ProductCard
        product={ product }
        initialValues={{
            count: 6,
            // maxCount: 10,
        }}
    >
        {
            ({ reset, count, isMaxCountReached, maxCount, increaseBy  }) => (
                <>
                    <ProductImage />
                    <ProductTitle />
                    <ProductButtons />
                </>
            )
        }
    </ProductCard>
```
