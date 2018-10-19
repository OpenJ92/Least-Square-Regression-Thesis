# Least-Square-Regression-Thesis

#### See pdf above to read the full paper

### Goal:

I sought to demonstrate the motivation, construction and application of Linear Least Square Regression.

### Motivation:

see: sections - Mapping: Point to Point, Mapping: Point to Function

The sections _Mapping: Point to Point_ and _Mapping: Point to Function_ were constructed to familiarize the reader with the move from considering functions x -f(parameters, form)-> y as simply belonging to the plane A(x,y) to belonging to the collection A(x,y) X B(parameters). 

We demonstrate the form of coefficents belonging to B(parameters) which when mapped to A(x,y) always contain the points Q = {(x0, y0), (x1, y1), (x2, y2)} in plane A(x,y). Considering all forms in B(parameters) containing Combinations_Choose_2(Q) we show by example that those forms intersect in plane B(parameters). We then demonstrate that Combinations_Choose_3(Q), there exist forms which do not simulteneously intersect showing that there exists no such form which describes all three points. This then begs the question, does there exist a form in B(parameters) that reasonabally represents the points Q belong to A(x,y)?

### Construction
see: Least Square Regression, Least Square Regression and Matrix Calculus, The Matrix Derivitive, The Weighted Matrix

In sections _Least Square Regression_, _Least Square Regression and Matrix Calculus_ and _The Matrix Derivitive_ we describe and formulate the method of Least Square Regression as a means to construct a model of the given data. 

In section _The Weighted Matrix_, I describe the action of the introduction of a weight term to our matrix form and propose a form for the elements of such a matrix. 

### Application
see: Experiments

I apply our method to forecast NYSE and NIST datasets. We use RSS to measure the goodness of fit for our model and demonstrate the effectiveness of the Weighted Matrix term.

### Conclusion

Model building is an incredibly useful tool.  It allows one to understand processes outside a first principle approach. I hope to be able to apply and extend this method in the months and years to come.
