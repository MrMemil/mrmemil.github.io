Today I had a lecture on the topic of Dual Spaces, and I wanted to explain my thoughts on the Topic. Dual Spaces 
and their corresponding Dual Bases, are apperenantly extreme useful tools, because of their very neet properties.
Essentially, the dual Space of a Vector space V is simply the Vector space of all linear Functions from V into our field. 
Written out, V* = Hom(V,K). As such sets of linear functions themselves form vector vector spaces with pointwise addition and 
scalar multiplication, this is of course a vector space. We can think of these functions as ways to "measure" vectors. 
The members of the dual space are called linear functionals, or covectors. One can wonder why these new covectors are named "dual"
as though they have some symmetry with the original vectors. The answer is that we can understand vectors themselves as functions,
simply from K to V. Vectors are simply directions waiting to be scaled by different inputs. We understand therefore that 
V is isomorphic to the space Hom(K,V). Using this interpretation, we see a certain symmetry and feel justified in naming V* dual spaces.

Importantly, we are able to find a very useful process by which we, given a Basis of V, can find a corresponding dual Basis of V*. 
This done in the following way, we must find functions such that when reciving all the different Basis vectors as inputs, the functions 
always return 0, except for with excactly one Basis vector, where the return value is 1. And of course, each function must return 1 
with a different Basis vector. Using this contruction, at the very least for finite dimensional Vs, we find a unique dual basis, since
the linearity combined with our contruction collapses the functions values at all other inputs. This is of course not a valid basis in
the case of V being infinately dimensional, because this set, while being linearly independant, does not span V* because linear combinations
are always finite. As such, in the case of V being infinately dimensional, V* is of strictly greater dimension. While for finite 
dimensions, this in fact proves that the dual space is isomophic to V. As the naive math student I am, I often believe that the contruction
of an isomophism collapses all further investigations, and that the structure can not be further studied. This is of course very much wrong.
The dual basis turns out to have extremely useful computational properties, in particular for solving systems of linear equations.
It turns out, that once we solve for the dual basis, we can easily solve all systems of linear equations using the same basis we contructed
our dual basis from. The reason for this, being that dual spaces allow us to simply read coefficients, instead of finding them, as the property
we defined for our dual basis, (that they return 1 for only one basis vector), completely collapses the equation. 
