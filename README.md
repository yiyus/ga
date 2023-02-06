# Geometric Algebra

Geometric algebra extends vector spaces with a geometric product, such that elements of higher dimensions can be created (eg planes in 2D, and volumes in 3D). Geometric algebra includes a number of other algebras without defining additional properties, including vectors, multivectors, complex and hiperbolic numbers, quaternions, dual quaternions, space-time algebra (relativity), multidimensional, projective, and conformal geometries, …

## Principles

1. Vector spaces (linear algebra)
2. Geometric product: associative product that extends the scalar product such that the product of parallel vectors is a scalar

From these basic principles, a number of properties and operations are defined, which allow the manipulation of geometric entities.

## The APL of algebra

- Developed long time ago, but other (suboptimal) solutions became mainstream for non-technical reasons
- More regular, consistent and intuitive than other alternatives
- Do more with less
- Most people who could benefit do not know about it, but it is strong in some fields and often considered a “secret weapon”
- Some renewed popularity thanks to the occasional youtube video or hackernews post

## Notations and implementations

There is no standard notation for the geometric product. The most common one is simple juxtaposition, but some authors use different symbols.

There are a number of additional products and operations which are usually defined when working with geometric algebras (inner and exterior product, antiproducts, reverses and complements, ...). Although some symbols are commonly used, there is again a number of possibilities, and no well stablished standard.

There is a number of GA texts that practically introduce all the needed notation from scratch. There is also a number of software libraries, written for different languages, and with different goals.

## Objective

The objective is to present an introduction to linear algebra, assuming only basic knowledge of linear algebra, using APL instead of traditional mathematical notation. This way, it is not neccessary to make distinctions between the theoretical concepts and its software implementation.

## Jupyter notebooks

### [Geometric Algebra](Geometric%20Algebra.ipynb)

Long notebook which introduces vector spaces and geometric algebra, in a non rigorous way, using Dyalog APL.

### [ga](ga.ipynb)

Short notebook to create ga Link namespace with the code in the Geometric Algebra notebook.

### [Each nested](https://github.com/yiyus/dyalog-jupyter-notebooks/blob/experiments/Each%20Nested.ipynb)

Development of the "Each Nested" operator used in the Geometric Algebra and ga notebooks to calculate inverses.

### TODO

- Vector spaces
- Compress / Expand scalars
- Geometric product
- Geometric operations

## Links

- [David Hestenes](https://geocalc.clas.asu.edu/html/Intro.html)
- [Alan Macdonald](http://www.faculty.luther.edu/~macdonal/#geometric-algebra)
- [Eric Lengyiel](https://projectivegeometricalgebra.org/)
- bivector.net
- [hn](https://hn.algolia.com/?q=%22geometric%20algebra%22) 
