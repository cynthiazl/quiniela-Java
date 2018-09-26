# quiniela-Java
Este es el código realizado en Java
```Java

package p.sp;

import java.awt.image.ReplicateScaleFilter;

public class act1_quiniela {

	static String[] sustituir = { "i", "j", "j2", "k", "k2", "l", "l2", "m", "m2", "n", "n2", "p", "p2", "q" };

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int contador = 0;

		for (int i = 1; i < 4; i++) {

			for (int j = 1; j < 4; j++) {

				for (int j2 = 1; j2 < 4; j2++) {

					for (int k = 1; k < 4; k++) {

						for (int k2 = 1; k2 < 4; k2++) {

							for (int l = 1; l < 4; l++) {

								for (int l2 = 1; l2 < 4; l2++) {

									for (int m = 1; m < 4; m++) {

										for (int m2 = 1; m2 < 4; m2++) {

											for (int n = 1; n < 4; n++) {

												for (int n2 = 1; n2 < 4; n2++) {

													for (int p = 1; p < 4; p++) {

														for (int p2 = 1; p2 < 4; p2++) {

															for (int q = 1; q < 4; q++) {

																contador++;

																String salida = 
																		i + "" + j + "" + j2 + "" + k + ""
																		+ k2 + "" + l + "" + l2 + "" + m + "" + m2 + ""
																		+ n + "" + n2 + "" + p + "" + p2 + "" + q;
																
																salida = salida.replace('3', 'X');
																
																System.out.println(salida);
																
															}
														}
													}
												}
											}
										}
									}
								}
							}
						}
					}
				}
			}
		}
		
		System.out.println(contador);
	}

}

