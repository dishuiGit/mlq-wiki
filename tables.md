### `table`
@startuml
!define TABLE (T,#FFAAAA)

class mlq_goods <<TABLE>> {
  departureTime : 时间
  departureTime : 时间
  departureTime : 时间
  departureTime : 时间
  departureTime : 时间
  departureTime : 时间
	departureTime : 时间
}


class mlq_product <<TABLE>>{
sdfsf:买书
}
class mlq_product_picture <<TABLE>>
class mlq_product_attr <<TABLE>>
class mlq_shop_info <<TABLE>>
class mlq_shop_info2 <<TABLE>>

mlq_goods "1" -- "*" mlq_product
mlq_goods "1" -- "*" mlq_product_picture
mlq_product "1" -- "*" mlq_product_attr
mlq_shop_info "1" -- "*" mlq_goods
mlq_shop_info2 "1" -- "*" mlq_goods
@enduml