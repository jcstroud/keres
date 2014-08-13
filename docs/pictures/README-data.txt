README for Example-Data-Results.pkl
===================================

"Example-Data-Results.pkl" was created like this:

.. code-block:: python

     import cPickle
     f = open("Example-Data-Results.pkl", "w")
     cPickle.dump(norm_data, f)
     cPickle.dump(((time, value), history, signoise), f)
     f.close()
