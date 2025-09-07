<h1 align="center">E-commerce backend</h1>

<br>

<div align="center" style="display: grid; justify-content: center;">

|                                                                  🌟                                                                   |                  Support this project                   |               
|:-------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------:|
|  <img src="https://raw.githubusercontent.com/ErikThiart/cryptocurrency-icons/master/32/bitcoin.png" alt="Bitcoin (BTC)" width="32"/>  | <code>bc1qs6qq0fkqqhp4whwq8u8zc5egprakvqxewr5pmx</code> | 
| <img src="https://raw.githubusercontent.com/ErikThiart/cryptocurrency-icons/master/32/ethereum.png" alt="Ethereum (ETH)" width="32"/> | <code>0x3147bEE3179Df0f6a0852044BFe3C59086072e12</code> |
|  <img src="https://raw.githubusercontent.com/ErikThiart/cryptocurrency-icons/master/32/tether.png" alt="USDT (TRC-20)" width="32"/>   |     <code>TKznmR65yhPt5qmYCML4tNSWFeeUkgYSEV</code>     |

</div>

<br>

> This is an overview of the project. Go to the submodule to see the implementation details of a specific service.

E-commerce backend based on the gRPC microservices ecosystem and Clean Architecture principles, includes: _authentication, shopping, ordering, promo usage, delivery, shipping tracking, etc_

____

[Try plugin for IntelliJ, make it easy to generate Protobuf code](https://plugins.jetbrains.com/plugin/21792-protobuf-blueprint)

[![Protobuf Blueprint](https://github.com/numq/protobuf-blueprint-plugin/blob/master/media/logo.png)](https://plugins.jetbrains.com/plugin/21792-protobuf-blueprint)

## Design features:

- Multilanguage: *Golang, TypeScript*
- *JWT* authentication
- *gRPC* based microservices
- *gRPC* based gateway

![Overview](./media/ecommerce-backend-overview.png)

### Authentication & authorization:

- [Authentication](https://github.com/numq/ecommerce-backend/tree/master/authentication)
- [Token](https://github.com/numq/ecommerce-backend/tree/master/token)
- [Account](https://github.com/numq/ecommerce-backend/tree/master/account)
- [Confirmation](https://github.com/numq/ecommerce-backend/tree/master/confirmation)

### Microservice infrastructure:

- [Gateway](https://github.com/numq/ecommerce-backend/tree/master/gateway)

### Domain specific services:

##### User related:

- [Profile](https://github.com/numq/ecommerce-backend/tree/master/profile)

##### Product related:

- [Category](https://github.com/numq/ecommerce-backend/tree/master/category)
- [Catalog](https://github.com/numq/ecommerce-backend/tree/master/catalog)
- [Search](https://github.com/numq/ecommerce-backend/tree/master/search)
- [Promo](https://github.com/numq/ecommerce-backend/tree/master/promo)

##### Purchase related:

- [Cart](https://github.com/numq/ecommerce-backend/tree/master/cart)
- [Payment](https://github.com/numq/ecommerce-backend/tree/master/payment)
- [Order](https://github.com/numq/ecommerce-backend/tree/master/order)

##### Shipping related:

- [Delivery](https://github.com/numq/ecommerce-backend/tree/master/delivery)
