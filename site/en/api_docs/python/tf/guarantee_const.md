

page_type: reference
<style> table img { max-width: 100%; } </style>


<!-- DO NOT EDIT! Automatically generated file. -->

# tf.guarantee_const

``` python
tf.guarantee_const(
    input,
    name=None
)
```



Defined in generated file: `tensorflow/python/ops/gen_array_ops.py`.

Gives a guarantee to the TF runtime that the input tensor is a constant.

The runtime is then free to make optimizations based on this.

Only accepts value typed tensors as inputs and rejects resource variable handles
as input.

Returns the input tensor without modification.

#### Args:

* <b>`input`</b>: A `Tensor`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor`. Has the same type as `input`.