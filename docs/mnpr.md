# MNPR

-----------

## Bilinear

### Template structure

This module takes a `FImpl` template argument, which is expected to be a fermion implimentation.

### Description



### Parameters

| Parameter   | Type           | Description                                    |
|-------------|----------------|------------------------------------------------|
| `qIn`     | `std::string`  | Name of the ingoing propagator      |
| `qOut`     | `std::string`  | Name of the outgoing propagator      |
| `pIn`   | `std::string`  | Ingoing fourmomentum         |
| `pOut`   | `std::string`  | Outgoing fourmomentum         |
| `output`         | `std::string`       | Specify the output location           |

### Dependencies

This module depends on a pair of propagators being generated.

### Products

The module produces 16 SpinColor vertices, one for every gamma-structure, which are saved to an hdf5 file at a specified location.

-----------

## ExternalLeg

### Template structure

This module takes a `FImpl` template argument, which is expected to be a fermion implimentation.

### Description


### Parameters

| Parameter   | Type           | Description                                    |
|-------------|----------------|------------------------------------------------|
| `qIn`     | `std::string`  | Name of the propagator      |
| `pIn`   | `std::string`  | Fourmomentum         |
| `output`         | `std::string`       | Specify the output location           |


### Dependencies

This module depends on a propagator being generated.

### Products

The module produces a SpinColorMatrix which is saved to an hdf5 file at a specified location.