

set(SOURCE
   ${SOURCE}
   ${CMAKE_CURRENT_SOURCE_DIR}/TradeInstance.cpp
   ${CMAKE_CURRENT_SOURCE_DIR}/TradeCase.cpp
   ${CMAKE_CURRENT_SOURCE_DIR}/AbstractTradeAccount.cpp
   ${CMAKE_CURRENT_SOURCE_DIR}/LongTradeAccount.cpp
   ${CMAKE_CURRENT_SOURCE_DIR}/ShortTradeAccount.cpp
   PARENT_SCOPE
)
set(HEADERS
   ${HEADERS}
   ${CMAKE_CURRENT_SOURCE_DIR}/TradeInstance.h
   ${CMAKE_CURRENT_SOURCE_DIR}/TradeCase.h
   ${CMAKE_CURRENT_SOURCE_DIR}/AbstractTradeAccount.h
   ${CMAKE_CURRENT_SOURCE_DIR}/LongTradeAccount.h
   ${CMAKE_CURRENT_SOURCE_DIR}/ShortTradeAccount.h
   PARENT_SCOPE
)
