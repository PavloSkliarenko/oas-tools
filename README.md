# oas-tools

This is fork of [oas-tools](https://github.com/isa-group/oas-tools) lib. Changed auth logic when `oasAuth: true`.
When JWT contains roles which are not described in your `securityFile` they will be skipped instead of an error.