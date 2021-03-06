`WriteGoodLintBear <https://github.com/coala-analyzer/coala-bears/tree/master/bears/natural_language/WriteGoodLintBear.py>`_
=====================

Lints the text files using ``write-good`` for improving proses.

See <https://github.com/btford/write-good> for more information.

`Supported Languages <../README.rst>`_
-----

* Natural Language

Settings
--------

+----------------------------+-------------------------------------------------------------+
| Setting                    |  Meaning                                                    |
+============================+=============================================================+
|                            |                                                             |
| ``allow_adverbs``          | Allows adverbs that can weaken the meaning, such as:        |
|                            | ``really``, ``very``, ``extremely``, etc. (Optional,        |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_ambiguous_words``  | Allows ``weasel words`` for example ``often``, ``probably`` |
|                            | (Optional, defaults to 'True'.)                             |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_cliche_phrases``   | Allows common cliche phrases in the sentence. (Optional,    |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_extra_words``      | Allows wordy phrases and unnecessary words. (Optional,      |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_passive_voice``    | Allows passive voice. (Optional, defaults to 'True'.)       +
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_repeated_words``   | Allows lexical illusions – cases where a word is repeated.  |
|                            | (Optional, defaults to 'True'.)                             |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_so_beginning``     | Allows ``So`` at the beginning of the sentence. (Optional,  |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``allow_there_is``         | Allows ``There is`` or ``There are`` at the beginning of    |
|                            | the sentence. (Optional, defaults to 'True'.)               |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_adverbs``          | Allows adverbs that can weaken the meaning, such as:        |
|                            | ``really``, ``very``, ``extremely``, etc. (Optional,        |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_ambiguos_words``   | Allows ``weasel words`` for example ``often``, ``probably`` |
|                            | (Optional, defaults to 'True'.)                             |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_cliche_exists``    | Allows common cliche phrases in the sentence. (Optional,    |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_extra_words``      | Allows wordy phrases and unnecessary words. (Optional,      |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_passive_voice``    | Allows passive voice. (Optional, defaults to 'True'.)       +
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_repeated_words``   | Allows lexical illusions – cases where a word is repeated.  |
|                            | (Optional, defaults to 'True'.)                             |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_so_beginning``     | Allows ``So`` at the beginning of the sentence. (Optional,  |
|                            | defaults to 'True'.)                                        |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+
|                            |                                                             |
| ``check_there_is``         | Allows ``There is`` or ``There are`` at the beginning of    |
|                            | the sentence. (Optional, defaults to 'True'.)               |
|                            |                                                             |
+----------------------------+-------------------------------------------------------------+


Dependencies
------------

.. code-block:: bash

    $ npm install write-good@0.9.1



Can Detect
----------

* Formatting
* Grammar

License
-------

AGPL-3.0

Authors
-------

* The coala developers (coala-devel@googlegroups.com)
