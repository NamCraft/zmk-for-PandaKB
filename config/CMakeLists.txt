# Teilt dem Protobuf-Compiler (Nanopb) den korrekten Pfad für die Studio-Messages mit
list(APPEND NANOPB_IMPORT_DIRS "${CMAKE_CURRENT_LIST_DIR}/../modules/msgs/zmk-studio-messages/proto/zmk")
