# Changelog

## [26.1-prototype.4]

### Added
- Space map and limited walk area
- Highlighted move/capture squares for all remaining pieces - rook, knight, bishop, queen, king
- Snap to space for all remaining pieces (was pawns only)
- Castling and en passant
- Pawn promotion popup (pick Queen / Rook / Bishop / Knight)
- Check and checkmate detection (can't leave your king in check; banner + locks the board)
- Draw detection (stalemate, insufficient material, 50-move, threefold repetition)
- Vote to reset the board after checkmate/draw
- Game commands: /tp, /resetboard, /clearside, /square
- Host admin commands: /kick, /ban, /unban, /sessionban, /sessionunban, /banlist, /bring, /announce
- Play Solo button to play against an AI(with 3 modes/difficult) so you don't have to be against someone (you can work with other people) (AI Mode 3 has lag, will be fixed before 26.1-alpha)
- You can see the version bottom left
- (For GitHub, not the game) CHANGELOG=(version).md

### Changed
- Turn-based now - can only grab a piece on its colour's turn
- On/Off Board square text now red for illegal moves (was green only)
- Player walks to the piece on release (was the piece snapping to the player)
- Releasing a piece where you picked it up no longer says "Illegal Move"

### Fixed
- None

### Removed
- None
