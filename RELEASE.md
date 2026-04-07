Release type: minor

This release attaches error details to Apollo Federation inline tracing (FTV1) trace nodes.

When a resolver raises an exception, the error message, location, and path are now included in the corresponding trace node, allowing Apollo Studio to display error information alongside timing data.
