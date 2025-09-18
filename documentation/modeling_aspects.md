
# :triangular_flag_on_post: What is modeled in LOD3?

There are several approaches to model Building in CityGML 2.0 (e.g. see [Biljecki et al.](http://pure.tudelft.nl/ws/portalfiles/portal/4377508/Biljecki2016to.pdf)). In our case, due to the acquisition geometry of MLS point clouds, the building objects consist of a very detailed representation of facade elements but on the other hand, it might lack roof elements and entities located in the Building's backyard. Thus, we encourage to see the list below for a detailed description of the Building in our Ingolstadt LOD3 dataset:

* :house: Building consists of:
  * Ground Surfaces
  * Roof Surfaces
  * Wall Surfaces
  * Outer Ceiling Surfaces
  * Outer Floor Surfaces
  * Closure Surfaces
  * Windows modeled in detail
  * Doors modeled in detail
  * Building Installations
    * Balconies
    * Passages
    * Arcades
    * Loggias
    * Stairs and Porches
    * (Some) Dormers
  * Textures (approximated based on visual inspection)

* :house: Building does **NOT** consist of:
  * Overhanging Building Elements
  * Roof structure details
  * Objects located in the Building's backyard (not facing the street)
  * Building Installations
    * Chimneys
    * Rain Gutters
    * (Some) Dormers
    * Real (e.g. orthophoto) textures

The terminology according to [SIG3D](https://en.wiki.quality.sig3d.org/index.php?title=Modeling_Guide_for_3D_Objects_-_Part_2:_Modeling_of_Buildings_(LoD1,_LoD2,_LoD3)).
