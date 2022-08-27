# Procedure
mysql procedure


CREATE PROCEDURE metehandb.updateSalesPrice(productId int, newSalesPrice double)
BEGIN
	update Product
	set salesPrice = newSalesPrice
	where Product.productId=productId;
END
