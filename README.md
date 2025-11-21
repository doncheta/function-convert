# function-convert
  function convert() external {
        if (hasClaimed[msg.sender]) {
            revert TokensClaimed();
          }
