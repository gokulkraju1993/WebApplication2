FROM microsoft/aspnetcore:1.1
ARG source
WORKDIR /app
EXPOSE 80
COPY ${source:-Docker} .
ENTRYPOINT ["dotnet", "WebApplication2.dll"]
