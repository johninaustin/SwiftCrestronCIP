# SwiftCrestronCIP
[![License](https://img.shields.io/github/license/cbw/SwiftCrestronCIP)](https://github.com/cbw/SwiftCrestronCIP/blob/master/LICENSE)

A Swift package for communicating with Crestron control processors via the Crestron over IP (CIP) protocol.

---

#### NOTICE: This module is not produced, endorsed, maintained or supported by Crestron Electronics Incorporated. 'XPanel', 'Smart Graphics' and 'SIMPL Windows' are all trademarks of Crestron. The author is not affiliated in any way with Crestron.

This Swift module was inspired by [Katherine Lenae's Python CIP client](https://github.com/klenae/python-cipclient).

This is a Swift-based socket client that facilitates communications with a Crestron control processor using the Crestron-over-IP (CIP) protocol. Familiarity with and access to Crestron's development tools, processes and terminology are required to configure the control processor in a way that allows this module to be used.

---

## Sample Programs

The [CIPSampleApp Swift application](./CIPSampleApp) demonstrates the use of this package. See the `README` file for information on building and running. The sample app requires the counterpart [Crestron sample program](./Crestron%20Sample%20Program) to be running on a Creston control system.
