# BOCoSy

This is our placeholder website for our tool BOCoSy.  
A source release will be available in late 2022.

## Usage

We provide a container image at `ghcr.io/reactive-systems/bocosy:hscc`.  
Just start it up and take a look inside. It contains its own readme.

### Current Limitations

The current implementation has some limitations which we will fix for the source release:

- The synthesized controller will have Mealy semantics and the plant models have to have Moore semantics.
- The reference plant model has to be deterministic.

## Further Reading

BOCoSy is based on [BoSy](https://www.react.uni-saarland.de/tools/bosy/) a tool and framework for bounded synthesis.

## Questions?

If you have any questions, contact [Malte Schledjewski](https://www.react.uni-saarland.de/people/schledjewski.html) via [email](mailto:malte.schledjewski@cispa.de?subject=BOCoSy).
