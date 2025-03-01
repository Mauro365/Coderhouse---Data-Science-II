# Coderhouse---Data-Science-II
Coderhouse---Data-Science-II

Una compañía de seguros de autos cuenta con una base de datos de los distintos individuos a los que les realizó una cotización de seguro. Este DataSet contiene características del individuo, características del contacto, variables asociadas al monto de la cotización y si finalmente el individuo contrató o no el servicio de seguros de autos. Con el fin de concentrar sus esfuerzos sobre los clientes más probables a comprar y no esforzarse en los menos probables, el objetivo de este análisis será predecir la variable Conversion_Status.

Variable objetivo:
  Conversion_Status (texto): binario que indica con "1" si el cliente compró o no.
  
Las variables del DataSet son:
  Age (numérico): Edad del sujeto
  Is_Senior (texto): Binario que indicado si la persona es o no mayor a 55 años
  Marital_Status (texto): Estado Civil
  Married_Premium_Discount (número): Descuento en caso de casado
  Prior_Insurance (texto): Duración del seguro anterior al actual
  Prior_Insurance_Premium_Adjustment (número): Descuento por duración del seguro anterior. 50 en caso de 1-5 años y 100 en caso de <1 año. 
  Claims_Frequency (número): frecuencia anual de reclamos.
  Claims_Severity (texto): severidad de los reclamos.
  Claims_Adjustment (número): ajuste por reclamos. (Frecuencia por severidad, considerando la severidad Low = 50, Medium = 100 y High = 200)
  Policy_Type (texto): tipo de cobertura (Full Coverage o Liability-Only)
  Policy_Adjustment (número): ajuste por Policy_Type (si es Liability-Only = -200, Full Coverage = 0)
  Premium_Amount (número): Promoción final.
  Safe_Driver_Discount (texto): binario que indica con "1" si corresponde descuento por buen conductor.
  Multi_Policy_Discount (texto): binario que indica con "1" si corresponde descuento por múltiples.
  Bundling_Discount (texto): binario que indica con "1" si corresponde descuento por paquetes.
  Total_Discounts (número): Indica el descuento total que corrresponde a las últimas 3 variables. Suma los últimos 3 y los multiplica por 50.
  Source_of_Lead (texto): medio de contacto con el cliente. Puede ser Online, Agent o Referral.
  Time_Since_First_Contact (número): tiempo en días desde el primer contacto.
  Inquiries (número): cantidad de consultas.
  Quotes_Requested (número): cantidad de cotizaciones solicitadas.
  Time_to_Conversion (número): tiempo estimado para la conversión.
  Credit_Score (número): puntaje por historial crediticio.
  Premium_Adjustment_Credit (número): ajuste que depende del historial crediticio. Si el primer dígito de Credit_Score es =>7, entonces -50, sino 50.
  Region (texto): tipo de región del conductor. Puede ser Rural, Suburban o Urban.
  Premium_Adjustment_Region (número): ajuste por región siendo Rural = 0, Suburban = 50 y Urban = 100.
