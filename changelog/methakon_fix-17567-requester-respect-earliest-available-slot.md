### Fixed

- Initial sync: peer selection for range requests now skips peers whose advertised `earliest_available_slot` is above the requested range's start slot, instead of requesting a range the peer can only answer `ResourceUnavailable`.