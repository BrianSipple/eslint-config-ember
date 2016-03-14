# 2.2.0
- Updated package dependencies to eslint@2.2.0
  - Awaiting resolution of a [current issue](https://github.com/babel/babel-eslint/issues/267) in eslint-babel before integrating eslint@2.3.0
- Switched to a versioning approach that attempts to mirror the current _major_._minor_ version of `eslint` being supported. 

# 0.2.1
- permit function expressions

# 0.2.0
- Disable rules which cause issues in all Ember apps
  - prefer-arrow-callback
  - no-invalid-this
  - prefer-template
  - no-underscore-dangle

# 0.1.0
- Update to eslint@1.1.3

# 0.0.5
- Ignoring func-names as native Ember doesn't use this convention

# 0.0.4
- Update to eslint-config-nightmare-mode@0.0.3
- Use latest browser version of nightmare-mode

# 0.0.3
- Added support for one-var usage when not using assignment
