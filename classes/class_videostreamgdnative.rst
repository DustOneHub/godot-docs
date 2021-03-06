:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VideoStreamGDNative.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VideoStreamGDNative:

VideoStreamGDNative
===================

**Inherits:** :ref:`VideoStream<class_VideoStream>` **<** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

:ref:`VideoStream<class_VideoStream>` resource for for video formats implemented via GDNative.

Description
-----------

:ref:`VideoStream<class_VideoStream>` resource for for video formats implemented via GDNative.

It can be used via `godot-videodecoder <https://github.com/KidRigger/godot-videodecoder>`_ which uses the `FFmpeg <https://ffmpeg.org>`_ library.

Methods
-------

+-----------------------------+---------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`get_file<class_VideoStreamGDNative_method_get_file>` **(** **)**                                  |
+-----------------------------+---------------------------------------------------------------------------------------------------------+
| void                        | :ref:`set_file<class_VideoStreamGDNative_method_set_file>` **(** :ref:`String<class_String>` file **)** |
+-----------------------------+---------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_VideoStreamGDNative_method_get_file:

- :ref:`String<class_String>` **get_file** **(** **)**

Returns the video file handled by this ``VideoStreamGDNative``.

----

.. _class_VideoStreamGDNative_method_set_file:

- void **set_file** **(** :ref:`String<class_String>` file **)**

Sets the video file that this ``VideoStreamGDNative`` resource handles. The supported extensions depend on the GDNative plugins used to expose video formats.

