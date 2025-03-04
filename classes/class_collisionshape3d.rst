:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/CollisionShape3D.xml.

.. _class_CollisionShape3D:

CollisionShape3D
================

**Inherits:** :ref:`Node3D<class_Node3D>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

A node that provides a :ref:`Shape3D<class_Shape3D>` to a :ref:`CollisionObject3D<class_CollisionObject3D>` parent.

.. rst-class:: classref-introduction-group

Description
-----------

A node that provides a :ref:`Shape3D<class_Shape3D>` to a :ref:`CollisionObject3D<class_CollisionObject3D>` parent and allows to edit it. This can give a detection shape to an :ref:`Area3D<class_Area3D>` or turn a :ref:`PhysicsBody3D<class_PhysicsBody3D>` into a solid object.

\ **Warning:** A non-uniformly scaled **CollisionShape3D** will likely not behave as expected. Make sure to keep its scale the same on all axes and adjust its :ref:`shape<class_CollisionShape3D_property_shape>` resource instead.

.. rst-class:: classref-introduction-group

Tutorials
---------

- :doc:`Physics introduction <../tutorials/physics/physics_introduction>`

- `3D Kinematic Character Demo <https://godotengine.org/asset-library/asset/126>`__

- `3D Platformer Demo <https://godotengine.org/asset-library/asset/125>`__

- `Third Person Shooter Demo <https://godotengine.org/asset-library/asset/678>`__

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +-------------------------------+-----------------------------------------------------------+-----------+
   | :ref:`bool<class_bool>`       | :ref:`disabled<class_CollisionShape3D_property_disabled>` | ``false`` |
   +-------------------------------+-----------------------------------------------------------+-----------+
   | :ref:`Shape3D<class_Shape3D>` | :ref:`shape<class_CollisionShape3D_property_shape>`       |           |
   +-------------------------------+-----------------------------------------------------------+-----------+

.. rst-class:: classref-reftable-group

Methods
-------

.. table::
   :widths: auto

   +------+------------------------------------------------------------------------------------------------------------------------------+
   | void | :ref:`make_convex_from_siblings<class_CollisionShape3D_method_make_convex_from_siblings>` **(** **)**                        |
   +------+------------------------------------------------------------------------------------------------------------------------------+
   | void | :ref:`resource_changed<class_CollisionShape3D_method_resource_changed>` **(** :ref:`Resource<class_Resource>` resource **)** |
   +------+------------------------------------------------------------------------------------------------------------------------------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_CollisionShape3D_property_disabled:

.. rst-class:: classref-property

:ref:`bool<class_bool>` **disabled** = ``false``

.. rst-class:: classref-property-setget

- void **set_disabled** **(** :ref:`bool<class_bool>` value **)**
- :ref:`bool<class_bool>` **is_disabled** **(** **)**

A disabled collision shape has no effect in the world.

.. rst-class:: classref-item-separator

----

.. _class_CollisionShape3D_property_shape:

.. rst-class:: classref-property

:ref:`Shape3D<class_Shape3D>` **shape**

.. rst-class:: classref-property-setget

- void **set_shape** **(** :ref:`Shape3D<class_Shape3D>` value **)**
- :ref:`Shape3D<class_Shape3D>` **get_shape** **(** **)**

The actual shape owned by this collision shape.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Method Descriptions
-------------------

.. _class_CollisionShape3D_method_make_convex_from_siblings:

.. rst-class:: classref-method

void **make_convex_from_siblings** **(** **)**

Sets the collision shape's shape to the addition of all its convexed :ref:`MeshInstance3D<class_MeshInstance3D>` siblings geometry.

.. rst-class:: classref-item-separator

----

.. _class_CollisionShape3D_method_resource_changed:

.. rst-class:: classref-method

void **resource_changed** **(** :ref:`Resource<class_Resource>` resource **)**

*Obsoleted.* Use :ref:`Resource.changed<class_Resource_signal_changed>` instead.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
.. |bitfield| replace:: :abbr:`BitField (This value is an integer composed as a bitmask of the following flags.)`
