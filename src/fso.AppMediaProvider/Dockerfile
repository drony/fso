FROM microsoft/dotnet:2.0-runtime

COPY ./publish /publish
WORKDIR /publish
EXPOSE 7100
ENTRYPOINT ["dotnet", "fso.AppMediaProvider.dll"]



