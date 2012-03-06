# About

This repository is a simple example how a valid environment for [awsenv][]
should look like. Everytime you see `STRIPPED`, I removed content and you have 
to insert something. After you replaced every `STRIPPED` you should be done.
Easy, huh?

## Private key and certificate

Save your private key in `pk-XXX.pem` and the certificate in `cert-XXX.pem`.
Both files can be accessed in the [security credentials][] section of your
[AWS][] account.

## Access key and secret

Also these files are accessible in the [security credentials][] section of your
[AWS][] account. Just write both values into the `credentials` file next to the
corresponding line (directly after the `=` without any quotes or spaces).

## Keypair

The keypair used to access [EC2][] instances via [ssh][]. [awsenv][] will
recognize all files that ends with `-keypair`.

# License

    Copyright 2009-2012 Michael Contento <michaelcontento@gmail.com>

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. 
    See the License for the specific language governing permissions and
    limitations under the License.

  [AWS]: http://aws.amazon.com
  [EC2]: http://aws.amazon.com/ec2
  [SSH]: http://en.wikipedia.org/wiki/Secure_Shell
  [Security Credentials]: https://aws-portal.amazon.com/gp/aws/securityCredentials
  [awsenv]: https://github.com/michaelcontento/awsenv
