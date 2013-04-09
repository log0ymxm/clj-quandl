# Clojure Quandl API Wrapper

Access the Quandl dataset API using Clojure

## Install

You can install this dependency from the clojars.org repository

    [clj-quandl "0.1.0-SNAPSHOT"]

## Usage

    (:use 'clj-quandl.core)
    (quandl "WHO/20800_148"
        :start-date "2010-07-01")

## License

Copyright © 2013

Distributed under the Eclipse Public License, the same as Clojure.
