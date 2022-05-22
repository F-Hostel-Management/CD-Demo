FROM mcr.microsoft.com/dotnet/aspnet:6.0

ARG PORT
ENV PORT=$PORT

WORKDIR /app
COPY . .

RUN ls -R

ENTRYPOINT ["dotnet", "Api.dll"]