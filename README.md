# 1. Two-factor Authentication for Keystone

Two-factor authentication adds an extra layer of security on top of user name
and password style authentication that Keystone supports by default. In this
scheme, in addition to supplying a user name and a password,
the user includes a code that changes frequently. The code is generated using
 a hardware device such as an RSA SecureID token, or apps like the Google
 Authenticator app on iOS, Android and BlackBerry that support
[TOTP](http://tools.ietf.org/html/rfc6238).

In this project, you will design and implement a Keystone API extension to
support two factor authentication that uses TOTP protocol. Here
are the project deliverables.

1. An API specification for two-factor authentication to support the following
  * Enable/disable two factor authentication for a user
  * Enable/disable two factor authentication for a project
  * Authentication with user name, password and a code
2. An API extension to Keystone.
3. A default implementation to support TOTP.
3. Unit tests
4. An extension to Horizon to enable a user or an admin to enable two
factor authentication
4. API support to `python-keystoneclient`

See http://throwingfire.com/you-can-be-a-twofactor-hero/ for an
example of two-factor authentication implemented in Python. Check
[AWS Multi-Factor Authentication](http://aws.amazon.com/iam/details/mfa/) for an example of how two-factor authentication works in a cloud.

# 2. Demo Code
Code can be found on the add-tfa branches of the submodules here. To use, follow our (soon to be created) guide.


