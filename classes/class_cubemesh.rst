.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the CubeMesh.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_CubeMesh:

CubeMesh
========

**Inherits:** :ref:`PrimitiveMesh<class_primitivemesh>` **<** :ref:`Mesh<class_mesh>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Generate an axis-aligned cuboid :ref:`PrimitiveMesh<class_primitivemesh>`.

Member Functions
----------------

+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_vector3>`  | :ref:`get_size<class_CubeMesh_get_size>`  **(** **)** const                                                    |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_subdivide_depth<class_CubeMesh_get_subdivide_depth>`  **(** **)** const                              |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_subdivide_height<class_CubeMesh_get_subdivide_height>`  **(** **)** const                            |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_subdivide_width<class_CubeMesh_get_subdivide_width>`  **(** **)** const                              |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_size<class_CubeMesh_set_size>`  **(** :ref:`Vector3<class_vector3>` size  **)**                      |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_subdivide_depth<class_CubeMesh_set_subdivide_depth>`  **(** :ref:`int<class_int>` divisions  **)**   |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_subdivide_height<class_CubeMesh_set_subdivide_height>`  **(** :ref:`int<class_int>` divisions  **)** |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_subdivide_width<class_CubeMesh_set_subdivide_width>`  **(** :ref:`int<class_int>` subdivide  **)**   |
+--------------------------------+----------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`Vector3<class_vector3>` **size** - Size of the cuboid mesh. Defaults to (2, 2, 2).
- :ref:`int<class_int>` **subdivide_depth** - Number of extra edge loops inserted along the z-axis. Defaults to 0.
- :ref:`int<class_int>` **subdivide_height** - Number of extra edge loops inserted along the y-axis. Defaults to 0.
- :ref:`int<class_int>` **subdivide_width** - Number of extra edge loops inserted along the x-axis. Defaults to 0.

Description
-----------

Generate an axis-aligned cuboid :ref:`PrimitiveMesh<class_primitivemesh>`.

Member Function Description
---------------------------

.. _class_CubeMesh_get_size:

- :ref:`Vector3<class_vector3>`  **get_size**  **(** **)** const

.. _class_CubeMesh_get_subdivide_depth:

- :ref:`int<class_int>`  **get_subdivide_depth**  **(** **)** const

.. _class_CubeMesh_get_subdivide_height:

- :ref:`int<class_int>`  **get_subdivide_height**  **(** **)** const

.. _class_CubeMesh_get_subdivide_width:

- :ref:`int<class_int>`  **get_subdivide_width**  **(** **)** const

.. _class_CubeMesh_set_size:

- void  **set_size**  **(** :ref:`Vector3<class_vector3>` size  **)**

.. _class_CubeMesh_set_subdivide_depth:

- void  **set_subdivide_depth**  **(** :ref:`int<class_int>` divisions  **)**

.. _class_CubeMesh_set_subdivide_height:

- void  **set_subdivide_height**  **(** :ref:`int<class_int>` divisions  **)**

.. _class_CubeMesh_set_subdivide_width:

- void  **set_subdivide_width**  **(** :ref:`int<class_int>` subdivide  **)**


