.. Google Style Guides documentation master file, created by
   sphinx-quickstart on Tue Jun 18 09:09:55 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Google Style Guides
===================

Every major open-source project has its own style guide: a set of conventions (sometimes arbitrary) about how to write code for that project. It is much easier to understand a large codebase when all the code in it is in a consistent style.

“Style” covers a lot of ground, from “use camelCase for variable names” to “never use global variables” to “never use exceptions.” This project (`google/styleguide <https://github.com/google/styleguide>`_) links to the style guidelines we use for Google code. If you are modifying a project that originated at Google, you may be pointed to this page to see the style guides that apply to that project.

This project holds the C++ Style Guide, Objective-C Style Guide, Java Style Guide, Python Style Guide, R Style Guide, Shell Style Guide, HTML/CSS Style Guide, JavaScript Style Guide, AngularJS Style Guide, Common Lisp Style Guide, and Vimscript Style Guide. This project also contains cpplint, a tool to assist with style guide compliance, and google-c-style.el, an Emacs settings file for Google style.

If your project requires that you create a new XML document format, the XML Document Format Style Guide may be helpful. In addition to actual style rules, it also contains advice on designing your own vs. adapting an existing format, on XML instance document formatting, and on elements vs. attributes.

The style guides in this project are licensed under the CC-By 3.0 License, which encourages you to share these documents. See `https://creativecommons.org/licenses/by/3.0/ <https://creativecommons.org/licenses/by/3.0/>`_ for more details.

The following Google style guides live outside of this project: Go Code Review Comments and Effective Dart.

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   Python Style Guide <pyguide/index>
