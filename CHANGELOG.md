## Release Notes

# 1.0.0

- Initial release

# 1.0.1

- Use publicly available version of joda-time

# 1.1.0

- Add a method to convert bitfield structs to bitfield longs
- Fix an off-by-one bug on bitfields
- Parser validates that names and numbers are not repeated
- Annotations for retired_ids and retired_wire_names enforced by codegen
- toBuilder returns a Builder.AllSpecified
- Builders can set bitfields via a struct

# 1.1.1

- Can configure Scala binary version in codegen plugin

# 1.2.0

- Cross compile against Scala 2.10.2

# 1.3.0

- Don't pull in unprefixed Scala library