..  Copyright (c) 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _piocore:

PlatformIO Core
===============

**PlatformIO Core** is a heart of whole PlatformIO ecosystem and consists of

* Multi-platform Build System
* Development platform and package managers
* :ref:`librarymanager`
* :ref:`ldf`
* :ref:`Serial Port Monitor <cmd_device_monitor>`
* Integration components (:ref:`ide` and :ref:`ci`).

**PlatformIO Core** is written in `Python 2.7 <https://www.python.org/downloads/>`_
and works on Windows, macOS, Linux, FreeBSD and *ARM*-based credit-card sized
computers (`Raspberry Pi <http://www.raspberrypi.org>`_,
`BeagleBone <http://beagleboard.org>`_,
`CubieBoard <http://cubieboard.org>`_,
`Samsung ARTIK <https://www.artik.io>`_, etc.).


**PlatformIO Core** provides a rich and documented Command Line Interface (CLI).
The other PlatformIO-based software and IDEs are based on **PlatformIO Core CLI**,
such as :ref:`pioide`. In other words, they wrap **PlatformIO Core** with own GUI.

.. note::

    Please note that you do not need to install **PlatformIO Core** if you
    are going to use :ref:`pioide`. **PlatformIO Core** is built into
    PlatformIO IDE and you will be able to use it within PlatformIO IDE Terminal.

    Also, PlatformIO IDE allows to install :ref:`piocore` Shell Commands
    (``pio``, ``platformio``) globally to your system via
    ``Menu: PlatformIO > Install Shell Commands``.

.. toctree::
    :maxdepth: 2

    installation
    quickstart
    userguide/index
