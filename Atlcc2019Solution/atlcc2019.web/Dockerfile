FROM microsoft/dotnet:2.2-aspnetcore-runtime
ARG source
WORKDIR /app
EXPOSE 80
COPY ${source:-bin/Release/netcoreapp2.2/publish} .
ENTRYPOINT ["dotnet", "atlcc2019.web.dll"]