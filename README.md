# Game of GraphQL

[![Build Status](https://travis-ci.org/kensho-technologies/game-of-graphql.svg?branch=master)](https://travis-ci.org/kensho-technologies/game-of-graphql)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Play around with compiled GraphQL queries using OrientDB's built-in Game of Thrones data set.

Get started:
```
docker-compose up
```

This will start a server on port `5000`. To run queries using compiled GraphQL,
simply `POST` them to its `/graphql` endpoint.

The `Demo` jupyter notebook has some pre-written queries that you can run, edit, and play
around with.

## Changing the server

If you make changes to the database or server code, remember to run `docker-compose build`
to rebuild their docker images before restarting them.

## Legal

All trademarks, service marks, trade names, trade dress, product names and logos appearing on
Game of GraphQL are the property of their respective owners, including in some instances
HBO and George R. R. Martin ("Marks"). No claim to such Marks is made here.
This project builds upon and extends a dataset provided by the OrientDB team
(https://orientdb.com/public-databases/GamesOfThrones.zip). The world of Game of Thrones
includes themes not appropriate for all audiences, discretion is advised.
This project is being made available for educational and informational purposes.

## License

Licensed under the Apache 2.0 License. Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language
governing permissions and limitations under the License.

Copyright 2018 Kensho Technologies, Inc.
