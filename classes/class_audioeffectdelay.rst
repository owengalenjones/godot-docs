.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the AudioEffectDelay.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_AudioEffectDelay:

AudioEffectDelay
================

**Inherits:** :ref:`AudioEffect<class_audioeffect>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Adds a Delay audio effect to an Audio bus. Plays input signal back after a period of time.

Two tap delay and feedback options.

Member Functions
----------------

+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_dry<class_AudioEffectDelay_get_dry>`  **(** **)**                                                               |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_feedback_delay_ms<class_AudioEffectDelay_get_feedback_delay_ms>`  **(** **)** const                             |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_feedback_level_db<class_AudioEffectDelay_get_feedback_level_db>`  **(** **)** const                             |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_feedback_lowpass<class_AudioEffectDelay_get_feedback_lowpass>`  **(** **)** const                               |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_tap1_delay_ms<class_AudioEffectDelay_get_tap1_delay_ms>`  **(** **)** const                                     |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_tap1_level_db<class_AudioEffectDelay_get_tap1_level_db>`  **(** **)** const                                     |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_tap1_pan<class_AudioEffectDelay_get_tap1_pan>`  **(** **)** const                                               |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_tap2_delay_ms<class_AudioEffectDelay_get_tap2_delay_ms>`  **(** **)** const                                     |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_tap2_level_db<class_AudioEffectDelay_get_tap2_level_db>`  **(** **)** const                                     |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_tap2_pan<class_AudioEffectDelay_get_tap2_pan>`  **(** **)** const                                               |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`    | :ref:`is_feedback_active<class_AudioEffectDelay_is_feedback_active>`  **(** **)** const                                   |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`    | :ref:`is_tap1_active<class_AudioEffectDelay_is_tap1_active>`  **(** **)** const                                           |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`    | :ref:`is_tap2_active<class_AudioEffectDelay_is_tap2_active>`  **(** **)** const                                           |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_dry<class_AudioEffectDelay_set_dry>`  **(** :ref:`float<class_float>` amount  **)**                             |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_feedback_active<class_AudioEffectDelay_set_feedback_active>`  **(** :ref:`bool<class_bool>` amount  **)**       |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_feedback_delay_ms<class_AudioEffectDelay_set_feedback_delay_ms>`  **(** :ref:`float<class_float>` amount  **)** |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_feedback_level_db<class_AudioEffectDelay_set_feedback_level_db>`  **(** :ref:`float<class_float>` amount  **)** |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_feedback_lowpass<class_AudioEffectDelay_set_feedback_lowpass>`  **(** :ref:`float<class_float>` amount  **)**   |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap1_active<class_AudioEffectDelay_set_tap1_active>`  **(** :ref:`bool<class_bool>` amount  **)**               |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap1_delay_ms<class_AudioEffectDelay_set_tap1_delay_ms>`  **(** :ref:`float<class_float>` amount  **)**         |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap1_level_db<class_AudioEffectDelay_set_tap1_level_db>`  **(** :ref:`float<class_float>` amount  **)**         |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap1_pan<class_AudioEffectDelay_set_tap1_pan>`  **(** :ref:`float<class_float>` amount  **)**                   |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap2_active<class_AudioEffectDelay_set_tap2_active>`  **(** :ref:`bool<class_bool>` amount  **)**               |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap2_delay_ms<class_AudioEffectDelay_set_tap2_delay_ms>`  **(** :ref:`float<class_float>` amount  **)**         |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap2_level_db<class_AudioEffectDelay_set_tap2_level_db>`  **(** :ref:`float<class_float>` amount  **)**         |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_tap2_pan<class_AudioEffectDelay_set_tap2_pan>`  **(** :ref:`float<class_float>` amount  **)**                   |
+----------------------------+---------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`float<class_float>` **dry** - Output percent of original sound. At 0, only delayed sounds are output. Value can range from 0 to 1. Default value: [code]1[/code].
- :ref:`bool<class_bool>` **feedback/active** - If [code]true[/code] feedback is enabled. Default value: [code]false[/code].
- :ref:`float<class_float>` **feedback/delay_ms** - Feedback delay time in milliseconds. Default value: [code]340[/code].
- :ref:`float<class_float>` **feedback/level_db** - Sound level for [code]tap1[/code]. Default value: [code]-6 dB[/code].
- :ref:`float<class_float>` **feedback/lowpass** - Low-pass filter for feedback. Frequencies below the Low Cut value are filtered out of the source signal. Default value: [code]16000[/code].
- :ref:`bool<class_bool>` **tap1/active** - If [code]true[/code], [code]tap1[/code] will be enabled. Default value: [code]true[/code].
- :ref:`float<class_float>` **tap1/delay_ms** - [b]Tap1[/b] delay time in milliseconds. Default value: [code]250ms[/code].
- :ref:`float<class_float>` **tap1/level_db** - Sound level for [code]tap1[/code]. Default value: [code]-6 dB[/code].
- :ref:`float<class_float>` **tap1/pan** - Pan position for [code]tap1[/code]. Value can range from -1 (fully left) to 1 (fully right). Default value: [code]0.2[/code].
- :ref:`bool<class_bool>` **tap2/active** - If [code]true[/code], [code]tap2[/code] will be enabled. Default value: [code]true[/code].
- :ref:`float<class_float>` **tap2/delay_ms** - [b]Tap2[/b] delay time in milliseconds. Default value: [code]500ms[/code].
- :ref:`float<class_float>` **tap2/level_db** - Sound level for [code]tap2[/code]. Default value: [code]-12 dB[/code].
- :ref:`float<class_float>` **tap2/pan** - Pan position for [code]tap2[/code]. Value can range from -1 (fully left) to 1 (fully right). Default value: [code]-0.4[/code].

Description
-----------

Plays input signal back after a period of time. The delayed signal may be played back multiple times to create the sound of a repeating, decaying echo. Delay effects range from a subtle echo effect to a pronounced blending of previous sounds with new sounds.

Member Function Description
---------------------------

.. _class_AudioEffectDelay_get_dry:

- :ref:`float<class_float>`  **get_dry**  **(** **)**

.. _class_AudioEffectDelay_get_feedback_delay_ms:

- :ref:`float<class_float>`  **get_feedback_delay_ms**  **(** **)** const

.. _class_AudioEffectDelay_get_feedback_level_db:

- :ref:`float<class_float>`  **get_feedback_level_db**  **(** **)** const

.. _class_AudioEffectDelay_get_feedback_lowpass:

- :ref:`float<class_float>`  **get_feedback_lowpass**  **(** **)** const

.. _class_AudioEffectDelay_get_tap1_delay_ms:

- :ref:`float<class_float>`  **get_tap1_delay_ms**  **(** **)** const

.. _class_AudioEffectDelay_get_tap1_level_db:

- :ref:`float<class_float>`  **get_tap1_level_db**  **(** **)** const

.. _class_AudioEffectDelay_get_tap1_pan:

- :ref:`float<class_float>`  **get_tap1_pan**  **(** **)** const

.. _class_AudioEffectDelay_get_tap2_delay_ms:

- :ref:`float<class_float>`  **get_tap2_delay_ms**  **(** **)** const

.. _class_AudioEffectDelay_get_tap2_level_db:

- :ref:`float<class_float>`  **get_tap2_level_db**  **(** **)** const

.. _class_AudioEffectDelay_get_tap2_pan:

- :ref:`float<class_float>`  **get_tap2_pan**  **(** **)** const

.. _class_AudioEffectDelay_is_feedback_active:

- :ref:`bool<class_bool>`  **is_feedback_active**  **(** **)** const

.. _class_AudioEffectDelay_is_tap1_active:

- :ref:`bool<class_bool>`  **is_tap1_active**  **(** **)** const

.. _class_AudioEffectDelay_is_tap2_active:

- :ref:`bool<class_bool>`  **is_tap2_active**  **(** **)** const

.. _class_AudioEffectDelay_set_dry:

- void  **set_dry**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_feedback_active:

- void  **set_feedback_active**  **(** :ref:`bool<class_bool>` amount  **)**

.. _class_AudioEffectDelay_set_feedback_delay_ms:

- void  **set_feedback_delay_ms**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_feedback_level_db:

- void  **set_feedback_level_db**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_feedback_lowpass:

- void  **set_feedback_lowpass**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_tap1_active:

- void  **set_tap1_active**  **(** :ref:`bool<class_bool>` amount  **)**

.. _class_AudioEffectDelay_set_tap1_delay_ms:

- void  **set_tap1_delay_ms**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_tap1_level_db:

- void  **set_tap1_level_db**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_tap1_pan:

- void  **set_tap1_pan**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_tap2_active:

- void  **set_tap2_active**  **(** :ref:`bool<class_bool>` amount  **)**

.. _class_AudioEffectDelay_set_tap2_delay_ms:

- void  **set_tap2_delay_ms**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_tap2_level_db:

- void  **set_tap2_level_db**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectDelay_set_tap2_pan:

- void  **set_tap2_pan**  **(** :ref:`float<class_float>` amount  **)**


