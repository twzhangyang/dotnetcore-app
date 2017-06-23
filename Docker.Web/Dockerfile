FROM microsoft/aspnetcore:1.1
WORKDIR /app
EXPOSE 80
COPY published ./
ENTRYPOINT ["dotnet", "Docker.Web.dll"]
