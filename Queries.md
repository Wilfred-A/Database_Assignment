SELECT * FROM suppliers
ORDER BY Country;

UPDATE Product_Hierarchy
SET product_name='Roofing Sheet',amount_required=2
WHERE product hierarchy='Wood';

SELECT DISTINCT product_name
FROM Product_Hierarchy;

SELECT * FROM Product_Supplier
WHERE supplied_to_date IN ('2-5-16','4-4-16');

SELECT *
FROM Suppliers
WHERE ROWNUM <=5;