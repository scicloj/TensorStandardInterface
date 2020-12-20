# Tensor Interface and Specification

## Purpose

In Clojure, a sequence is something that implements the [Seq interface](https://clojure.org/reference/sequences#_the_seq_interface).
A sequence is anything that implements `first`, `rest`, and `cons`. Likewise, all
[data structures](https://clojure.org/reference/data_structures) follow certain rules. These rules have provided
rich interoperability, clarity of thought, and an entire community of developers and enthusiasts. 

The primary purpose of this project is to provide an interface or set of interfaces and specifications to define the Clojure Tensor, sometimes known as
an N-Dimensional-Array, with the same care, quality, philosophy, and expectations that a Clojure developer would expect of core datatype.

The secondary purpose is to provide example reference implementations of the Clojure Tensor Interface for the popular scientific
Clojure computing backends, such as [dtype-next](https://cnuernber.github.io/dtype-next/), [Deep-Diamond](https://github.com/uncomplicate/deep-diamond),
[Neanderthal](https://github.com/uncomplicate/neanderthal), and others.

The third purpose is to provide a stable API for dependent interfaces and datatypes.
One example of a dependent datatype is the dataset, which is a tabular data represenation
that has various concretions in the Scientific Clojure ecosystem but no abstract interface. 

The fourth and final purpose is to provide a stable API and layer of abstraction for authors of scientific tools, user-facing libraries,
and domain specific applications to have meaningful discussion and knowledge sharing with the community
and to be able to pick from the most performant backends for their purposes without needing to be experts
in the concrete implementations of the backend library.

## Contributing

To suggest improvements, please create an issue.

Pull requests are welcome as a form of discussion for enhancing the specification.

## License

MIT for now, but this is basically a placeholder.  Open to suggestions.
