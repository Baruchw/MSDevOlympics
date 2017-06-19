##Docker File For ASP.net core app
FROM microsoft/aspnetcore-build
WORKDIR /app

COPY . .
RUN dotnet restore
RUN dotnet publish
