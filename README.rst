.. role:: bash(code)
   :language: bash

.. role:: python(code)
   :language: python

.. image:: https://api.travis-ci.org/undertherain/benchmarker.svg?branch=master
    :target: https://travis-ci.org/undertherain/benchmarker
    :alt: build status from Travis CI

========
Synopsis
========

Benchmarker is a modular framework to automate a set of performance benchmarks, mostly for deep learning. 

===
Run
===

python3 -m benchmarker --framework=theano --problem=conv2d_1 --path-out=./

==========
Motivation
==========

various devices, frameworks und underlying software stacks, network architectures etc.

============
Installation
============

Clone, install required packages
for example by running

``git clone --recursive https://github.com/undertherain/benchmarker.git``

``pip3 install [--user] -r requirements.txt``


=============
API Reference
=============

under development 


============
Contributors
============

Aleksandr Drozd

Kevin Brown

Artur Podobas

Mateusz Bysiek

=======
License
=======

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


