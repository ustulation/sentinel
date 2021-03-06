# Sentinel

Confirm group based consensus on messages in a p2p network

|Crate|Travis|Appveyor|Coverage|
|:------:|:-------:|:-------:|:-------:|
|[![](http://meritbadge.herokuapp.com/sentinel)](https://crates.io/crates/sentinel)|[![Build Status](https://travis-ci.org/dirvine/sentinel.svg?branch=master)](https://travis-ci.org/dirvine/sentinel)|[![Build status](https://ci.appveyor.com/api/projects/status/pjtc7tybh0k78e1f?svg=true)](https://ci.appveyor.com/project/dirvine/sentinel)|[![Coverage Status](https://coveralls.io/repos/dirvine/sentinel/badge.svg)](https://coveralls.io/r/dirvine/sentinel)|

| [API Documentation](http://dirvine.github.io/sentinel/sentinel/)| [MaidSafe System Documention](http://systemdocs.maidsafe.net/) | [MaidSafe web site](http://www.maidsafe.net) | [Safe Community site](https://forum.safenetwork.io) |

#Overview

###Pre-requisite:
None

##Todo Items

- [x] Restructure generic types
- [ ] Move Frequency to separate Statistics crate as it is used by Sentinel, but equally by routing for merging messages
- [ ] Replace return type Option<(Request, MergedMessageFromClaims)> to rx-channel

##External Todo Items

- [ ] On Accumulator crate:
    - [ ] Only store one value on identical values received
