# Botilleria-Code

class Products
{
   #Atributos#
   Type_product= #tipo de producto
   Name= #nombre del producto
   Company= #nombre de la Marca
   Price= #Precio del producto
   Barcode= #identificacion de producto
   Expiration_date= #fecha de vencimiento
   Cuantity= #cantidad del producto
   Supplier= #Empresa proveedora
   Qr_code= #numero de codigo qr

   #Fin seccion Atributos##
}

class Client
{
   #Atributos#
   id= #rut del cliente
   birthday= #fecha de nacimiento
   Payment= #pago
   Payment type= #tipo de pago
   ticket= #se emitio boleta true o false
   #Fin seccion atributos#   
 }
    
 #Fin secciion Atributos##
   
 ##metodos (funcion)##
{
   Open_shop(open) #abrir la tienda
   Remove_products(remove) #retirar productos vencidos
   Replenish_products(newproducts) #reponer los productos
   Clean_shop(Clean) #mantener la limpieza del local
   Serve_customers(service) #atender cliente
   Charge_price(charge) #cobrar el precio total
   Give_change(change) #dar el cambio en caso de que el cliente pague con mas dinero del que se le cobro
   Close_shop(close) #cerrar la tienda 
}
