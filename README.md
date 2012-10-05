rdflib-rdfa-serializer
======================

RDFa serialization for RDFLib.

Copy this file into the plugins folder of RDFLib, then register the plugin:

  register('rdfa', Serializer,
                'rdflib.plugins.serializers.rdfa', 'RdfaSerializer')

