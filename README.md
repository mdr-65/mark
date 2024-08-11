def count_b(code_number):
    spell_c = 0
    rome_c = 0
    for code in code_number:
        if str(code).endswith('42'): spell_c += 1
        last2num = int(str(code)[-2:]) 
        if 50 <= last2num <= 80: rome_c += 1
    return spell_c, rome_c

code_number = [2736649, 72376423, 16738712987, 32492, 90129343, 9828342, 9730373, 2398932465, 273626389, 2837273732, 87425672151, 728374363, 652365456, 32872487387498, 256235634366, 236762476, 67263672342, 83748374, 28384309402365, 2387647589, 2746480, 28364876452373, 823749283479, 29837482937454, 6725347623942, 176842]
spell_c, rome_c = count_b(code_number)

print(f"Книг с заклинаниями: {spell_c}")
print(f"Книг с историей Древнего Рима: {rome_c}")
