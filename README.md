# sat-defi
/**
 *Submitted for verification at Etherscan.io on 2019-11-14
*/

// hevm: flattened sources of /nix/store/8xb41r4qd0cjb63wcrxf1qmfg88p0961-dss-6fd7de0/src/dai.sol
pragma solidity =0.5.12;

// /nix/store/8xb41r4qd0cjb63wcrxf1qmfg88p0961-dss-6fd7de0/src/lib.sol
// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.

// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.

// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.

/* pragma solidity 0.5.12; */

contract LibNote {
    event LogNote(
        bytes4   indexed  sig,
        address  indexed  usr,
        bytes32  indexed  arg1,
        bytes32  indexed  arg2,
        bytes             data
    ) anonymous;

    modifier note {
        _;
        assembly {
        
        >>
  <head>
    <meta charset="utf-8">2021.1.2
    <meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no">
    <!-- <link rel="icon" type="image/x-icon"  href="static/favicon.ico"> -->
    <link rel ="shortcut icon" type="image/x-icon" href="static/favicon.ico">
    <title>SASscan</title>
  <link href="./static/css/p_index.3c0d172d7e92134c5faa15446b7a9d1c.css?7659dfece60514ff06c2" rel="stylesheet"></head>
  <body>
    <div id="pc"></div>
  <script type="text/javascript" src="./static/js/manifest.2f9d994fb047fe005a6e.js?7659dfece60514ff06c2"></script><script type="text/javascript" src="./static/js/vendor.dfce8afd3ea613ceba5b.js?7659dfece60514ff06c2"></script><script type="text/javascript" src="./static/js/p_index.bf36cb73100951eec227.js?7659dfece60514ff06c2"></script></body>

SAT\u53cc\u91cd\u5408\u7ea6\u300b
C576a6002Fb72d1BB85FFd9f51C2A48C495bFCcc
\u521d\u59cb\u5408\u7ea6\u6267\u884c 1/2
\u89e6\u53d1\u6807\u51c6\uff1a3200000\u4e0a\u94fe\uff0c2880000\u6d41\u901a
\u94fe\u4e0a\u673a\u5236

\u4e8c\u7ea7\u5408\u7ea6\u6267\u884c
\u89e6\u53d1\u6807\u51c6\uff1ahalvings 1/2
30% \u4ea7\u51fa\u8fbe\u5230106\u4e07\u679a
\u6267\u884c\u4ef7\u683c\u94fe\u63a5\u300b
SAS \u94c6\u9489\u5e02\u503c\u4ea7\u51fa\u7b97\u529b
\u5408\u7ea6\u5730\u5740
C576a6002Fb72d1BB85FFd9f51C2A48C495bFCcc
\u521d\u59cb\u5408\u7ea6\u300bQ3-Q4
\u4e8c\u7ea7\u5408\u7ea6\u300bQ3-Q4
execution time 2021.1.15
Time of issue 2021.1.2

            // log an 'anonymous' event with a constant 6 words of calldata
            // and four indexed topics: selector, caller, arg1 and arg2
            let mark := msize                         // end of memory ensures zero
            mstore(0x40, add(mark, 288))              // update free memory pointer
            mstore(mark, 0x20)                        // bytes type data offset
            mstore(add(mark, 0x20), 224)              // bytes size (padded)
            calldatacopy(add(mark, 0x40), 0, 224)     // bytes payload
            log4(mark, 288,                           // calldata
                 shl(224, shr(224, calldataload(0))), // msg.sig
                 caller,                              // msg.sender
                 calldataload(4),                     // arg1
                 calldataload(36)                     // arg2
                )
        }
    }
}
