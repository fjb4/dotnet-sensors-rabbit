# Accelerator Log

## Options
```json
{
  "gitBranch" : "main",
  "gitUrl" : "https://github.com/fjb4/dotnet-sensors-rabbit.git",
  "projectName" : "dotnet-sensors-rabbit"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug dotnet-sensors-rabbit.sln matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug k8s/rabbitmq-cluster.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug k8s/rabbitmq-clusterresource.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug k8s/rabbitmqcluster-read-write.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug k8s/rabbitmqcluster-reader.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug k8s/resource-claims-rmq.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug project.toml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Controllers/HomeController.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Models/ErrorViewModel.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Program.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/RabbitMqHelper.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/SensorHostedService.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/ServiceBindingsReader.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Home/Index.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Home/Start.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Home/Stop.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Shared/Error.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Shared/_Layout.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Shared/_Layout.cshtml.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/Shared/_ValidationScriptsPartial.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/_ViewImports.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/Views/_ViewStart.cshtml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/dotnet-sensors-rabbit.csproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/css/site.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/favicon.ico matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/js/site.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.rtl.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.rtl.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.rtl.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-grid.rtl.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.rtl.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.rtl.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.rtl.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-reboot.rtl.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.rtl.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.rtl.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.rtl.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap-utilities.rtl.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.rtl.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.rtl.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.rtl.min.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/css/bootstrap.rtl.min.css.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.bundle.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.bundle.js.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.bundle.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.bundle.min.js.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.esm.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.esm.js.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.esm.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.esm.min.js.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.js.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/bootstrap/dist/js/bootstrap.min.js.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery/LICENSE.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery/dist/jquery.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery/dist/jquery.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery/dist/jquery.min.map matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation/LICENSE.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation/dist/additional-methods.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation/dist/additional-methods.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation/dist/jquery.validate.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation/dist/jquery.validate.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation-unobtrusive/LICENSE.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/wwwroot/lib/jquery-validation-unobtrusive/jquery.validate.unobtrusive.js matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug src/wwwroot/lib/jquery-validation-unobtrusive/jquery.validate.unobtrusive.min.js matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┗ ┗ ┗ ┗  Info Will replace [https://github.com/fjb4/dotnet-sensors.git->https://github.com/f...(truncated), master->main]
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
