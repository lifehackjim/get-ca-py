API Reference
=============

Classes
-------

Store Classes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autoclass:: cert_human.CertStore
    :members:
    :undoc-members:
    :show-inheritance:
    :private-members:
    :member-order: bysource

.. autoclass:: cert_human.CertChainStore
    :members:
    :undoc-members:
    :show-inheritance:
    :private-members:
    :member-order: bysource

WithCert Classes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autoclass:: cert_human.HTTPSConnectionWithCertCls
    :members:
    :undoc-members:
    :show-inheritance:
    :private-members:
    :member-order: bysource

.. autoclass:: cert_human.ResponseWithCertCls
    :members:
    :undoc-members:
    :show-inheritance:
    :private-members:
    :member-order: bysource

Exception Classes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autoexception:: cert_human.CertHumanError
    :members:
    :undoc-members:
    :show-inheritance:
    :private-members:
    :member-order: bysource

Functions
---------

Get Cert Functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autofunction:: cert_human.get_response
.. autofunction:: cert_human.ssl_socket
.. autofunction:: cert_human.test_cert

WithCert Functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autofunction:: cert_human.enable_urllib3_patch
.. autofunction:: cert_human.disable_urllib3_patch
.. autofunction:: cert_human.urllib3_patch
.. autofunction:: cert_human.using_urllib3_patch
.. autofunction:: cert_human.check_urllib3_patch

Conversion Functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autofunction:: cert_human.asn1_to_der
.. autofunction:: cert_human.asn1_to_x509
.. autofunction:: cert_human.der_to_asn1
.. autofunction:: cert_human.der_to_x509
.. autofunction:: cert_human.pem_to_x509
.. autofunction:: cert_human.pems_to_x509
.. autofunction:: cert_human.x509_to_asn1
.. autofunction:: cert_human.x509_to_der
.. autofunction:: cert_human.x509_to_pem

Utility Functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. autofunction:: cert_human.clsname
.. autofunction:: cert_human.hexify
.. autofunction:: cert_human.indent
.. autofunction:: cert_human.write_file
.. autofunction:: cert_human.read_file
.. autofunction:: cert_human.find_certs
