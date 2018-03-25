# Private

# XCTest
- [XCTest Documentation](https://developer.apple.com/documentation/xctest)

# API

## CollectionView API 
- 네트워크 통신 후 페이징할 때 cell reuse cycle 질문 (deinit 호출)
- `func insertItems(at indexPaths: [IndexPath])`
- `func performBatchUpdates(_ updates: (() -> Void)?, 
              completion: ((Bool) -> Void)? = nil)`
- `reloadData()`
- `reloadItems(at:)`
