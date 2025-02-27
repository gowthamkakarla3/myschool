# Use the official ASP.NET runtime image
FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS runtime

# Set the working directory inside the container
WORKDIR /app

# Copy all the prebuilt API files from the host to the container
COPY . .

# Expose the API port (adjust if your API runs on a different port)
EXPOSE 5000
EXPOSE 5001

# Set the entry point for the container to run the API
ENTRYPOINT ["dotnet", "School_API.dll"]
