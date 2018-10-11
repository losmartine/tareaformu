<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>formulario</title>
	<link rel="stylesheet" href="css/estilo.css">
</head>
<body>
<fieldset>
	<div id="identificador"> 	
	
			<h1>formulario</h1>
			
			<form  method="post" action="#" >
				
				<ul>
					<li>
					<label for="nombre" class="titulo">Nombre<br>completo <span style="color:red">*</span></label>
					<div class="controles">
						<span class="completo">
							<input type="text" id="nombre" name="nombre" placeholder="tipo texto">
							<label for="nombre">Nombre</label>
						</span>
						<span class="completo">
							<input type="text" id="apellido1" name="apellido1" placeholder="tipo texto">
							<label for="apellido1">Primer apellido</label>
						</span>
						<span class="completo">
							<input type="password" id="apellido2" name="apellido2" placeholder="tipo pass">
							<label for="apellido2">Segundo apellido</label>
						</span>
						<span class="fecha">
							<input type="date" id="nfecha" name="fecha" placeholder="06/06/2006">
							<label for="fecha">Fecha de nacimiento</label>
						</span>
					</div>
					</li>
					<li>
						<label for="direccion" class="titulo">Dirección <span style="color:red">*</span></label>
						<div class="controles">
							<span class="completo">
								<input id="direccion" name="direccion" placeholder="adolfo lopez mateos">
								<label for="direccion">Calle, privada</label>
							</span>
							<span class="calle">
								<input id="direccion" name="direccion">
								<label for="direccion">numero</label>
							</span>
							<span class="casa">
								<input id="interior" name="interior" type="range">
								<label for="interior">interior</label>
							</span>
							<span class="tercio">
								<input id="codigo postal" name="codigo postal">
								<label for="codigo postal">C.P.</label>
							</span>
							<span class="dostercios">
								<input id="municipio" name="municipio">
								<label for="municipio">Municipio</label>
							</span>
							<span class="edo">
				    			<select id="provincia" name="provincia">
       								<option value="Aguascalientes">Aguascalientes</option>
									<option value="Baja California">Baja California</option>
									<option value="Baja California Sur">Baja California Sur</option>
									<option value="campeche">Campeche</option>
									<option value="Coahuila">Coahuila</option>
									<option value="Colima">Colima</option>
									<option value="Chiapas">Chiapas</option>
									<option value="Chihuahua">Chihuahua</option>
									<option value="Ciudad de México">Ciudad de México</option>
									<option value="Durango">Durango</option>
									<option value="Guanajuato">Guanajuato</option>
									<option value="Guerrero">Guerrero</option>
									<option value="Hidalgo">Hidalgo</option>
									<option value="Jalisco">Jalisco</option>
									<option value="Mexico">EdoMex</option>
									<option value="Michoacán">Michoacán</option>
									<option value="Morelos">Morelos</option>
									<option value="Nayarit">Nayarit</option>
									<option value="Nuevo León">Nuevo León</option>
									<option value="Oaxaca">Oaxaca</option>
									<option value="Puebla">Puebla</option>
									<option value="Queretaro">Queretaro</option>
									<option value="Quintana Roo">Quintana Roo</option>
									<option value="San Luis Potosi">San Luis Potosí</option>
									<option value="Sinaloa">Sinaloa</option>
									<option value="Sonora">Sonora</option>
									<option value="Tabasco">Tabasco</option>
									<option value="Tamaulipas">Tamaulipas</option>
									<option value="Tlaxcala">Tlaxcala</option>
									<option value="Veracruz">Veracruz</option>
									<option value="Yucatán">Yucatán</option>
									<option value="Zacatecas">Zacatecas</option>
      							</select>
      							<label for="provincia">Estado</label>
      						<span class="dostercios">
      							<select id="pais" name="pais">
        							<option value=""></option>
        							<option value="pais1">México</option>
        							<option value="pais2">Estados Unidos</option>
        							<option value="pais3">Colombia</option>
      							</select>
      							<label for="pais">País</label>
    						</span>
    						</span>
						</div>
					</li>
					<li>
						<label for="email" class="titulo">Email</label>
						<div class="controles">
							<span class="controles">
								<input type="text" id="email" name="email" value="">
							</span>
						</div>
					</li>	
					<li>
						<label for="telefonofijo" class="titulo">Teléfono<span style="color:red">*</span></label>
							<div class="controles">
								<span class="mitad">
									<input id="telefonofijo" name="telefonofijo" value="">
									<label for="telefonofijo">Fijo</label>
								</span>
								<span class="mitad">
									<input id="telefonomovil" name="telefonomovil" value="">
									<label for="telefonomovil">Celular</label>
								</span>
							</div>
						</li>
					<li>
						<label for="otros" class="titulo">Otros <span style="color:red">*</span></label>
						<div class="controles">
							<span class="extra">
									<input id="hora" name="hora" value="" type="time">
									<label for="horal">Hora de registro</label>
							</span>
							<span class="extra" >
									<input id="sobrenombre" name="sobrenombre" value="" disabled>
									<label for="horal">Apodo</label>
							</span>
						</div>
					</li>
					<li class="botones">
						<input type="submit" id="alta" value="Dame de alta -->" />
					</li>
					<li class="botones">
						<input type="submit" id="borrar" value="Borrar -->" />
					</li>
				</ul>
			</form>
		</fieldset>
	</div>
</body>
</html>
ejemplo de formulario
