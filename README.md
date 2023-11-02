# Arduino-2687365
Lo que comprendimos del video fue: 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
El codificador rotatorio estaría conectado a la placa de Arduino en la cual irían conectados un pin A Y un pin B cabe recalcar que ambos pines tienen un voltaje alto ya predeterminado, 
el pin c que sería el codificador rotatorio que, en forma de engranaje, hará contacto con los pines A y B, que a su vez estaría conectado en el gnd, 
cuando entran en contacto el pin A o el Pin B con el pin C estas tendrán un voltaje de 0 pero cuando no haga contacto con el pin C tendrán un voltaje alto,
dependiendo del eje en el que se gire el codificador, el pin A o el Pin B alguno de los dos tendrá una interrupción en su voltaje, por ejemplo: 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
sí giramos en sentido horario por lógica el primer pin en recibir una interrupción sería el pin A, por ende, hasta que no se dé el siguiente giro no se cambiara el voltaje  
del pin B, por lo tanto, en un punto ambos quedarían con voltaje 0 pero no al mismo tiempo ya que el primer pin con interrupción es el A, pero el B sigue manteniendo su voltaje, 
pero si se da otro giro ambos pines quedan sin voltaje, pero si se vuelve a dar otro giro el pin A quedaría con un voltaje alto y el B seguiría con su voltaje de 0, y por un último giro ambos voltajes quedarían como en el inicio. 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
sí giramos en sentido antihorario se repetiría lo mismo, pero al revés ya que empezaría por el pin B y terminaría con el pin A 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------




