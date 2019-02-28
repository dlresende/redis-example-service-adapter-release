# redis-example-service-adapter-release

This project relies on the Pivotal Services SDK, available to customers and partners for download at [network.pivotal.io](http://network.pivotal.io)

---

An example release of an on-demand broker service adapter for Reids.

This is intended as an example and should not be used in production.

## Setting up the Redis Adapter with the On-Demand Service Broker

To see an example manifest that deploys the Redis adapter with the On-Demand Service Broker (ODB), please see the [example manifest](docs/example-manifest.yml) and [example Redis BOSH release](https://github.com/pivotal-cf-experimental/redis-example-service-release).

Alternatively you can use the simplified `redis-example-service-adapter.yml` manifest which requires only a frew variables to configure.

---

## Development

1. Clone this repository
1. `cd` into this repository
1. `source .envrc`. You can automate this with [direnv](https://github.com/direnv/direnv).
1. Follow the instructions in the [service adapter](https://github.com/pivotal-cf-experimental/redis-example-service-adapter).

---

README - PIVOTAL SDK - MODIFIABLE CODE NOTICE

The contents of this GitHub repository available at https://github.com/pivotal-cf-experimental/redis-example-service-adapter-release are licensed to you
under the terms of the Pivotal Software Development Kit License Agreement ("SDK EULA")
and are designated by Pivotal Software, Inc. as "Modifiable Code."

Your rights to distribute, modify or create derivative works of all or portions of this
Modifiable Code are described in the Pivotal Software Development Kit License Agreement
("SDK EULA") and this Modifiable Code may only be used in accordance with the terms and
conditions of the SDK EULA.

Unless required by applicable law or agreed to in writing, this Modifiable Code is
provided on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
express or implied. See the SDK EULA for the specific language governing permissions and
limitations for this Modifiable Code under the SDK EULA.
