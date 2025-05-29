# simple-web-app

## Servlet
- DoEditProductServlet
  - @WebServlet("/doEditProduct")
  - doGet()
    - request.getParameter()
    - new Product()
    - DBUtils.updateProduct()
    - forward() or redirect()

## Bean
- Product
  - code
  - name
  - price

## Utility
- DBUtils
  - updateProduct()
- MyUtils
  - getStoredConnection()

## View (JSP)
- editProductView.jsp
- productListView.jsp

## Config
- web.xml