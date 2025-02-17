Penalized Synthetic Control Method
==================================

The penalized synthetic control method is due to
`Abadie & L'Hour <https://www.jmlr.org/papers/volume19/17-777/17-777.pdf>`_.

This version of the synthetic control adds a penalization term to the loss
function that has the effect of serving to reduce the interpolation bias.

The :class:`PenalizedSynth` class
*********************************

The :class:`PenalizedSynth <pysyncon.PenalizedSynth>` class implements the penalized
synthetic control method. The expected way to use the class is to first create a
:class:`Dataprep <pysyncon.Dataprep>` object that defines the study data and
then use it as input to a :class:`PenalizedSynth <pysyncon.RobustSynth>` object. See the
`examples folder <https://github.com/sdfordham/pysyncon/tree/main/examples>`_
of the repository for examples illustrating usage.

.. autoclass:: pysyncon.PenalizedSynth
   :members:
   :inherited-members: