#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-stretch-slim AS base

WORKDIR /app
COPY DevOpsAssignment/app/publish .
ENTRYPOINT ["dotnet", "DevOpsAssignment.dll"]
EXPOSE 80
EXPOSE 443
