.. |organization| replace:: scipion-chem
.. |repository| replace:: scipion-chem-toxcsm

========================================
Toxicity prediction of small ligands scipion plugin
========================================
**Documentation under development, sorry for the inconvenience**
Scipion framework plugin for the use of toxCSM software tool.
  
========================================
Install this plugin
========================================
You will need to use `Scipion3 <https://scipion-em.github.io/docs/docs/scipion
-modes/how-to-install.html>`_ to run these protocols.


- **Install the stable version**

    Through the plugin manager GUI by launching Scipion and following **Others** >> **Plugin Manager**

    or

.. parsed-literal::

    scipion3 installp -p \ |repository|\ 


- **Developer's version**

    1. Download repository:

    .. parsed-literal::

        git clone \https://github.com/\ |organization|\ /\ |repository|\ .git

    2. Install:

    .. parsed-literal::

        scipion3 installp -p /path/to/\ |repository|\  --devel
  
========================================
Protocols
========================================
This plugin contains the following protocols:

**None for now**

========================================
Packages & enviroments
========================================
Packages installed by this plugin can be located in ``/path/to/scipion/software/em/``.


As of today, Scipion does not automatically uninstall the conda enviroments created in the installation process when uninstalling a plugin, so keep this list in mind if you want to clean up some disk space if you need to uninstall this one.


========================================
Changelog
========================================
All the recent version changes can be found `here <https://github.com/scipion-chem/scipion-chem-toxcsm/blob/devel/CHANGES.rst>`_.
