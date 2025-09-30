## [0.1.21] - 2025-09-30

### 

- Removed commit groups
## [0.1.20] - 2025-09-30

### 

- Added release commits filter
- Changed to post-release-hook (reverted)
- Changed to post-release-hook
## [0.1.19] - 2025-09-30

### 

- Added cliff.toml config
## [0.1.18] - 2025-09-30

### 

- Added cliff.toml
## [0.1.17] - 2025-09-30

### 

- Updated pre-release-commit-message
- Added shared-version
## [0.1.16] - 2025-09-30

### 

- Updated pre-release-commit-message
## [0.1.15] - 2025-09-30

### 

- Pre-release-commit-message (reverted)
- Updated pre-release-commit-message
- Updated pre-release-hook
- Fixed git-cliff version name
- Fixed git-cliff exec
- Removed dev-version
- Removed changelog
- Renamed release.toml
- Added changelog gen (part 3)
## [0.1.14] - 2025-09-30

### 

- Release ieee1905 version 0.1.14
## [0.1.13] - 2025-09-30

### 

- Release ieee1905 version 0.1.13
- Added changelog gen (part 2)
- Added changelog gen
## [0.1.12] - 2025-09-30

### 

- Release ieee1905 version 0.1.12
- Added pre-release-hook
## [0.1.11] - 2025-09-30

### 

- Release ieee1905 version 0.1.11
- Added empty CHANGELOG.md
## [0.1.10] - 2025-09-30

### 

- Release ieee1905 version 0.1.10
- Added CHANGELOG.md
## [0.1.9] - 2025-09-30

### 

- Release ieee1905 version 0.1.9
- Added idea folder
- Merge pull request #50 from rdkcentral/feature/actions/main-cla

Deploy cla action
- Deploy cla action
- Update README.md

moving delivery to wiki
- Update README.md
## [0.1.8] - 2025-09-17

### 

- Release ieee1905 version 0.1.8
- Merge pull request #35 from rdkcentral/release/v0.1.8

Release/v0.1.8
- Merge pull request #31 from witold-kowolik/reorganization_of_unit_tests_#24

[#24] Reorganization of unit tests
- [#24] Reorganization of unit tests [4/4]

Part 4/4: tlv_lldpdu_codec.rs

Reorganize unit tests accordingly to following list of types:

1. internal functions
2. content fragmentation and reassembly
3. serializing and parsing
4. testing with malformed data

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#24] Reorganization of unit tests [3/4]

Part 3/4: registration_codec.rs

Reorganize unit tests accordingly to following list of types:

1. internal functions
2. content fragmentation and reassembly
3. serializing and parsing
4. testing with malformed data

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#24] Reorganization of unit tests [2/4]

Part 2/4: cmdu_handler.rs

Reorganize unit tests accordingly to following list of types:

1. internal functions
2. content fragmentation and reassembly
3. serializing and parsing
4. testing with malformed data

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#24] Reorganization of unit tests [1/4]

Part 1/4: cmdu_codec.rs

Reorganize unit tests accordingly to following list of types:

1. internal functions
2. content fragmentation and reassembly
3. serializing and parsing
4. testing with malformed data

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- Merge pull request #30 from witold-kowolik/documentation_of_unit_tests_#23

[#23] Documentation of unit tests
- [#23] Documentation of unit tests [8/8]

Part 8/8: tlv_lldpdu_codec.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [7/8]

Part 7/8: tlv_cmdu_codec.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [6/8]

Part 6/8: sdu_codec.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [5/8]

Part 5/8: registration_codec.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [4/8]

Part 4/8: lldpdu_codec.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [3/8]

Part 3/8: cmdu_reassembler.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [2/8]

Part 2/8: cmdu_handler.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#23] Documentation of unit tests [1/8]

Part 1/8: cmdu_codec.rs

Add general and internals description for every unit test.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- Merge pull request #29 from witold-kowolik/message_id_generator_unit_tests_#22

[#22] Check correctness of generation of subsequent message id values
- [#22] Check correctness of generation of subsequent message id values

After reaching 0xFFFF value of message id the next value of 0
after overflow should be skipped and corrected to 1.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- Merge pull request #28 from witold-kowolik/test_for_cmdu_fragment_duplicates_#21
- [#21] Recognize and report CMDU fragment duplicates

Currently CMDU reassembler doesn't recognize duplicated CMDU fragments
while reassembling.
Add detection and reporting of this particular case.
Add unit test to cover this specific case.

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#18] CMDU reassembler related unit tests [3/3]

Part 3/3: registration_codec.rs

Cover several test cases with unit tests:
- verification of empty fragment
- verification of missing last fragment
- verification of elapsed time > 3 seconds
- verification of out of order fragments
- verification of missed fragment in the middle of CMDU chain

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#18] CMDU reassembler related unit tests [2/3]

Part 2/3: cmdu_codec.rs

Cover several test cases with unit tests:
- verification of empty fragment
- verification of missing last fragment
- verification of elapsed time > 3 seconds
- verification of out of order fragments
- verification of missed fragment in the middle of CMDU chain

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- [#18] CMDU reassembler related unit tests [1/3]

Part 1/3: cmdu_reassembler.rs

Cover several test cases with unit tests:
- verification of empty fragment
- verification of missing last fragment
- verification of elapsed time > 3 seconds
- verification of out of order fragments
- verification of missed fragment in the middle of CMDU chain

Release/v0.1.8

Signed-off-by: Witold Kowolik <witold.kowolik@cognizant.com>
- Merge pull request #27 from piotr-przybyla-2311451/bump_versions
- [#25] bump last crate versions into 0.1.8

Crates versions have been upgraded to latest.

Signed-off-by: Piotr Przybyla <piotr.przybyla@cognizant.com>
- [#17] Clean up TLV based fragmentation feature 0.1.8

TLV based fragmentation option has been removed
from code base.
Conditional compilations parameter is also removed.
Only size based fragmentation is used.
## [0.1.7] - 2025-09-09

### 

- Release ieee1905 version 0.1.7
- Merge pull request #12 from rdkcentral/release/v0.1.7

Release/v0.1.7
- Adding change log processing 0.1.7
- Removing change log in 0.1.7
## [0.1.6] - 2025-09-05

### 

- Release ieee1905 version 0.1.6
- Merge pull request #11 from rdkcentral/release/v0.1.6

adding change log processing 0.1.6
- Adding change log processing 0.1.6
## [0.1.5] - 2025-09-05

### 

- Release ieee1905 version 0.1.5
- Merge pull request #10 from rdkcentral/release/v0.1.5

tuning change log processing for 0.1.5
- Tunning change log processing for 0.1.5
## [0.1.4] - 2025-09-05

### 

- Release ieee1905 version 0.1.4
- Merge pull request #9 from rdkcentral/release/v0.1.4

adding change log processing 0.1.4
- Adding change log processing 0.1.4
## [0.1.3] - 2025-09-04

### 

- Release ieee1905 version 0.1.3
- Merge pull request #8 from rdkcentral/release/v0.1.3

test release 0.1.3
- Test release 0.1.3
## [0.1.2] - 2025-09-04

### 

- Release ieee1905 version 0.1.2
- Merge pull request #7 from rdkcentral/release/v0.1.2

Release/v0.1.2
- Test release 0.1.2
- Merge pull request #6 from rdkcentral/main

Merge back from main release 0.1.1
- Merge pull request #5 from rdkcentral/release/v0.1.1

Adding info about how to use releases
- Adding info about how to use releases
## [0.1.1] - 2025-09-02

### 

- Release ieee1905 version 0.1.1
- Adding support for automatic releases
- Initial commit
