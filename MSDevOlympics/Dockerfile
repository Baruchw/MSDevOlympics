FROM microsoft/aspnetcore-build
WORKDIR /app

COPY MSDevOlympics.csproj .
RUN dotnet restore

COPY . .
#RUN dotnet publish --output /out/ --configuration Release
EXPORT 8000