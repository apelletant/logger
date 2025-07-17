Simple go logger

Example usage:
logger := NewCustomLogger(true) // enable debug logs
logger.Info("Application started", "port", 8080)
logger.Error("Database connection failed", err, "host", "localhost")
logger.Warn("Deprecated API endpoint used", "endpoint", "/old-api")
logger.Debug("User data", "userID", 123, "email", "user@example.com")
logger.Success("User created successfully", "userID", 456)
