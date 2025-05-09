# go-errorx

> A flexible and extensible error handling library for Go.

## ✨ Features

- Centralized error construction and categorization
- Framework adapters (Gin first, Echo/GRPC ready)
- Error code mapping and serialization
- Plug-in support for reporter/recovery/suppressor

## 📦 Project Structure

```
go-errorx/
├── errorx/         # Core error types and builder
├── category/       # Error category definitions
├── coder/          # Error code registration and lookup
├── contextual/     # Context propagation for error tracking (e.g., traceId)
├── mapper/         # Error to HTTP/gRPC status mapping
├── middleware/     # Gin, Echo, and other framework adapters
├── reporter/       # Interfaces for error reporting (e.g., Sentry)
├── recovery/       # Error fallback and retry strategies
├── suppressor/     # Suppress known errors to reduce noise
├── serializer/     # Output formatting for errors
└── examples/       # Sample usage (Gin, etc.)
```

## 🔧 Usage (Coming Soon)

1. Add to your `go.mod`:

```bash
go get github.com/yingfeidai/go-errorx
```

## 📌 License

MIT
