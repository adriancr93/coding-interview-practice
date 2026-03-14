# Coding Interview Practice

This repository is organized to help you practice technical interview problems in multiple programming languages.

## Structure

```
├── dotnet
│   └── runner
│       └── Program.cs
│
├── java
│   └── runner
│       └── Main.java
│
├── go
│   └── runner
│       └── main.go
│
├── node
│   ├── javascript
│   │   └── runner.js
│   └── typescript
│       └── runner.ts
│
└── README.md
```

## How to Run the Runners

### .NET
```
cd dotnet/runner
# If not initialized, run:
dotnet new console -n Runner -o .
dotnet run
```

### Java
```
cd java/runner
javac Main.java
java Main
```

### Go
```
cd go/runner
go run main.go
```

### Node.js (JavaScript)
```
cd node/javascript
node runner.js
```

### Node.js (TypeScript)
```
cd node/typescript
npx ts-node runner.ts
```

You can place your interview problem code in the corresponding runner file for each language.