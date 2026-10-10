# NEXORA Chess — Flutter starter

## Included
- Home dashboard, demo sign-in, profile and settings screens.
- Dark/purple theme and reusable widgets.
- Interactive chessboard UI: tap a piece, then tap a square to move it.
- Flutter SDK only; no third-party runtime packages.

## Important limitations
The board is a UI prototype, **not a complete chess rules engine**. It allows a selected piece to move to any square and does not validate legal moves, check/checkmate, castling, en passant, promotion, draw rules, PGN/FEN, clocks or undo. Profile stats are sample data. Sign-in and Google button are placeholders; no Firebase or real authentication. Settings are not persisted.

## Run in Kleancode IDE
1. Create/open a Flutter project.
2. Copy this ZIP's files into the project, keeping folder paths. `pubspec.yaml` belongs in the root and Dart files under `lib/`.
3. Run `flutter pub get` if the IDE offers the action.
4. Open `lib/main.dart` and press Run.

Next step: integrate a chess rules package and add tests before treating any move as legal. Add Stockfish and real authentication as separate later steps.