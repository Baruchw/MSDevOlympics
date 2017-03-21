FROM microsoft/aspnetcore-build
WORKDIR /app

COPY . .
RUN dotnet restore
RUN dotnet publish
COPY . .

EXPORT 8000