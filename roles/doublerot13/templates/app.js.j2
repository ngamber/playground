var http = require('http');
var PORT = process.env.PORT || 5000;
//var pg = require('pg');
//var connectionString = "pg://{{db_user}}:{{db_password}}@localhost:5432/{{db_name}}";
var geoip = require('geoip-lite');

http.createServer(function (req, res) {
  console.log('%d request received', process.pid);
  var ip = req.headers["x-forwarded-for"] || request.connection.remoteAddress;
  var geo = geoip.lookup(ip);
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.write('Your ip is: ');
  res.write(ip);
  res.write('\n');
  res.write('You live in ');
  res.write(JSON.stringify(geo["city"]));
  res.end();

}).listen(PORT);

/*
pg.connect(connectionString, function(err, client){
if (err) {
  console.log ( err );
} else {
  pg.end();
}

});
*/
console.log('%d listening on %d', process.pid, PORT);
