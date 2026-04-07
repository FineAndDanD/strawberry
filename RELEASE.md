Release type: patch

This release attaches error details to Apollo Federation inline tracing (FTV1) trace nodes. This was missing in the original FTV1 addition made in [0.314.0](https://github.com/strawberry-graphql/strawberry/releases/tag/0.314.0).

When a resolver raises an exception, the error message, location, and path are now included in the corresponding trace node, allowing Apollo Studio to display error information alongside timing data.
