# Botilleria-Code

class Products
{
   #Atributos#
   Type_product= #tipo de producto
   Name= #nombre del producto
   Company= #nombre de la Marca
   Price= #Precio del producto
   Barcode= #identificacion de producto
   Alcohol_grade= #En caso de ser de tipo alcohol registrar su grado de alcohol
   Elaboration_date= #fecha de elaboracion
   Expiration_date= #fecha de vencimiento
   Cuantity= #cantidad del producto en la tienda
   Supplier= #Empresa proveedora

   #Fin seccion Atributos##
}

class Client
{
   #Atributos#
   id= #rut del cliente
   birthday= #fecha de nacimiento
   Payment= #pago
   Payment_type= #tipo de pago
   ticket= #se emitio boleta true o false
   #Fin seccion atributos#   
 }
    
   #Fin secciion Atributos##
   
   ##metodos (funcion)##
{
   Open_shop(open) #abrir la tienda
   Remove_products(remove) #retirar productos vencidos
   Replenish_products(newproducts) #reponer los productos
   Clean_shop(clean) #mantener la limpieza del local
   Serve_customers(service) #atender cliente
   Charge_price(charge) #cobrar el precio total
   Give_change(change) #dar el cambio en caso de que el cliente pague con mas dinero del que se le cobro
   Give_product(giveproducts) #entregar el product cuando se realize el pago
   Register_buyandsales(register) #registrar compras y ventas del local
   Manage_accounts(manage) #administrar y llevar las cuentas del local
   Close_shop(close) #cerrar la tienda
}
