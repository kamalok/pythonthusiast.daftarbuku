# pythonthusiast.daftarbuku
test penggunaan git


message = 'hello wordl!'
nama = 'kamal OK'
usia = 17
lingkar_perut = 20.5

print (message)
print (nama)
print (usia)

if usia <= 6:
    print ('jangan nonton film dewasa')
    print ('masih kecil')
else :
    print ('menuju dewasa')

if lingkar_perut < 30:
    print ('kurus')
elif lingkar_perut < 40:
    print ('Lintuh')
else:
    print('Gembrottttt')

for i in range (2,3):
    print(message)

while usia > 0:
    print ('usia saat ini %s' % usia)
    print ('masih hidup')
    usia = usia - 1

daftar_nama= ['saya','aku','aing','myself']
print (daftar_nama)
daftar_nama.append('aing')
daftar_nama.append('saya')
print (daftar_nama)

for dn in daftar_nama:
    print("nama lain anda adalah %s, padahal nama aslimu itu %s lho!" %(dn, nama) )

manusia ={}
manusia['nama'] = 'Kamal OK'
manusia['sex'] = 'laki laki'
manusia['alamat'] = 'jalancagak'
manusia['status'] = 'pelajar'
print(manusia)
manusia['nama'] = 'Kamal Okehh'
print(manusia)
manusia ['alamat']='jalancagak'
print (manusia)

import json
print (json.dumps(manusia))
