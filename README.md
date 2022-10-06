# RRCMS (Running Room Crew Management System) for IRCTC Locopilots 
Detailed Description here: https://abhishekgautam101.github.io/rrcms/

[![RRCMS](data:image/jpg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBT/wAARCAE3AOkDASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD4Fl1MaZeaNM0YH2C7kjYhsFkLByD6ffcVzcs8tppF/Ycb7LUVkVh/CxDI3/oKflW3riie1umyCzGC5HuCGVj+bLWPqIL6jrOeTc2yXIx/eYpIf5tUrYtouX+qrNdeK4wjRR6ikd5Gueh8xHH/AI67VPb6kJLywlZGAutHktH/ANoqjxr+qLWbGTNe2UzLzc6c8YA5yVjeNf1jFS6PKijQbib/AFcd6YTn+6Gjc5/77NaJ6k2LumastrbeE7p8qljeyo5H/PPejn/0NqrSXJtvDuo2YVkaDVY3RT2ykoIP/fC/lWfhk0G6VhiSC8jwPTKuD+qitDUmF1qHiJ0/1Jf7Uo+sgC/pJVXGbOsajb3V74x8lWMV4I7uMkY25lRuf+/lV9Svobma4lQlQ2m2xPHIZFiDfqtZszmW+dU6S6ch+uyFWP6pT43DRW//AE10+XP4GTH/AKCKT1QXPa/g1KIvHOowqkASS2R0NsCFdQ74bB6ZBFfRlpHlFNfMXwNlLeOYW6iTTWOd2clZQPU/rg8dK+prVD5a8YrxMQvfOylsKse1sHoalSIB0PfIqYJQi4Yd+a5ep0X0PPvihEVttW6HEM3/AKBXzVrMR/4Rl244vApGOeUb/CvqH4kQNN/a6YxmOYc/9cq+ZfEEbQ+HZFI4N2pz6/I1dlP4Tlfx/Ib4Tj/4luT/AHjVjXxjTXz3K/8AoQo8LIBpCkjks386f4kGLAD/AGh/jWxSOUf/AFJqOMfrU78Qke4pI07kVmygZflH1FX/AAhEHhtycjhm/wA/nVGc7IZCBnaCcfhW54TjJgh9os/yprYTPSPhjaibxlZ5OAiyNnH+wf6172u0xYLHceSa8e+DUBl8UTNtBCWzEk44yVFe1Lbzh+WGw9gBz+lcVVty3OqmrRK3lJhgHI3Z+b+deafHu5Nr4GWJXDm5uo4m+nzN/NBXp88TRDOfkPfA4rxH9om822miWisdjSSylfdQoB/8eNKjfmQT+FnE/Dy0zcSykE4jIGPUkf4GsjxBds/iq8KHIjUqAfUtx+iGus+HUCjT55mHcc49Bn+tcRMDPe3twASzy4P4D/65r1vI8mL1CK6keTaVHINRmZrUBFVc9elLDG3mEsDn3FMuwTIcDvxWVk5HW5NQuhs12zwlTj5uw7VD/Z1x6frT4oTLcRRnqxArqPMT+6PyqZbjvpqef6XbJf6Q8UsbiUWU0S8EHzI2D4P4JTrfw5FfTaDPltl9YyQYBH3h5kY/9lqTQpJLO5mERiVftKgEDKqsq4cgZ6dRg/zFLZ6oIrGxlNqkYsb07FUt+7Jw2OScjIbg+g989/S5ylDT9Hhhj8NXUsshiTUfsspOPlXej8cf7bVXHh0QeH7xWmYSafqfkMpXuVYZ/Hyv5Vr3tzb2mmXkElq2y3vlbYs2CJCHGQSOFGwccnkc8VE2rQ3l54iga3kAu2jvZGWQDDbsKwGOAfNOQT3PNUgY3xBoGL7xPD5mVhkWdAIwMr5mB/469Ok8P77q5hEp2zaNHcbtuM7Yo3I+mUNXr29gudRvJpI5S9zYoH+cYX5EO4epG0ceoPrxINVjWbTHEZlkGmyWy/PjzExKmCMHBOG5zxkenMpsVkZFj4f8280gRzH/AEvTbjqucMBOgA/75FUrfSxHaaXcCXcZY7iAqRwMbv8A4vNbmiapG954f8qJ90M7W8e5s7tzZIbj/pp+Wap21xaCxsIR5mEu3MZyCcsEBU+2AOR6Hjnh3YWO5+BrLF440n758zT2jDsuAcCNiB9Of/1k19c2kZ8kHFfHnwYuvO8c+E3O/eyTRNlsplYtuFHbhFJ9z24z9n2sZEIGMdK8vEr3zopbCRxEjJH4Uot9rZPercMRHrUhiy3I6elcqWpvfQ4H4ix4bW26hIJj+PlY/rXzF4tjz4fGOiXSD/yG1fWPj6y8yDxGR1FvI5Pt5Wf6V8l+JMt4f54ZrpTj/gBrpht8zm+0L4YTOlIOxY/zpPEylbKMesg/kam8MqP7Jix0yf503xPj7HECM/vAf0Na3saLQ5SVdsX4gURrzU0yAxjqPmpI1APOai5RXuCBa3hP9wj+Q/rXU+GIwsKjGNsSj/P5Vyt6B5E3PXj9RXbaDCEjkH+7n8v/AK9PoT1PX/ghaJJcatKW+ZURQc9iSSP/AB2vYgyqEDAnaPXoPWvNfgdZxx6RqEz8mWdUHI/hGf8A2avTHYZYADAz3rz6mszrjpFFHU2MiqAq4643HrXzj+0DdGXxRYWoI2w2m7aD0LO364UV9FX0rAsc8Hof5V8wfFt2vfiTfIxzs8mPP/AFJ/VjWtFLmMqrfLqa+gRtY+Dp5MkEq5GPYbf6V5/AzJGxJKl5Hfr2LHH6Yr0PU9ukeAy+0gtEDk+/zkV56kG63i/eDIRc59cV6LVjzoJt6Dll3ct+lR7329anjtgIy5IPbr3pk0ITLblwBWcbanbJNJIZp6GXUcqCzICQPfoP51t/2VP/AJFVPC9q0tzLIMZyAPf/ADxXa7Lb/noPzFS3YGm2eS+EtWttL8XxSX9pHfxmD95DIV27lyp7HGM9x1Ge9egR+LPCpG2Xw7aLHDMfMXzoRvOSAXJUZ74Jx1rhPEliLHxe8Q+XbcSxEbv4JQXXj0+Y9MfnVe60aOa5volnIeazEwAj6qpViVOeW+U8e/WvQg1KKZyO6dj1CfxX4QkWYXPhy1lYus0v763y4JB59V+fgn25quuq+BXlnZ/Dqx+Yqliktud0QC4UfvBlQEHI9K8xttA+031rGJX3Xli/lFoyNwRWXnBOD+7HHPTr0os9C+0HRTFcnF5bXFtEZY9u5iZFw3J2nDgDr07VohXPVbi58CzmRTpEkbvCRGymI7U2spAxLyOCOKS3XwLNPD5Oj3A2LttyMtsO7PaTnlv1ryLRfDL6lF4duIrpDE87WymRSGPzglSBnB+c9+46c4uWXhW4stI09kvYB5F/IGc7xhyseE+71+QnPTpz6HKPm8j1GDSfAkcdi8Ol3qCFzKrJFIcP8vzffPHyjimReF/AbQw7bS9ixmUMbe4O6QA7SPmOBnHtxXk+o+HbnT7HUC1zHtt71ImHmY8tj5nDehO3qOOD6Gm6zpt1btrgykflaim7Mo/dZ80AH06j8j6GjlBy8jp/hMq2Hj7w42CrjUposZBGCjKAeMg57Z/AdT91adDugBOCCBXw14TkMXifQWxOqprqINozFzK2cnP3sOPwxX3ZpqlLZcc8V5eL0aZrSFEBTJxn0FTCHNJcb1ORjFWLQ+aee1cCnd2Ok5DxtbK51zc7LmxkG0MRnMNfIPihf+JMo5/4+B9PuGvr/wCKcZhTWgOM2mf/AByvkTxQcaKVwP8Aj4U/+Omu2G3zOW/vh4XjP9kx+mW/maZ4oTNvDj+//Q1Z8Mp/xJYfq3/oRqDxOcRQL0JYn8h/9etGdCRzNwv7tfdqaF5/Cpp1ykYPrSKMg1mUZswLzRp2dwP/AB6vRNOTMbsBgFhwOOgFcLFFvvbRSOsgP9a9CsYtkOGxyT0quhnvI9x+EduIfCrOw/1szuPwCj+legWaI2HRMk/Nz6/5FeYeB/GWkaP4Zs7a5vEiuIy5ZTGx4LEjOPbFdGnxP0CNGAvoiMcfIw5/KuGTV2ztUZWWhu3EipPtIAI+YY9a+S/El3/avjzV7kfMGvJmUn0DEL/IV79efEjR1SeQXqlyDwEPX26V8++E1a98QQMy72kmDEn3cE/1rbDb3OXEXUdTpviVLt8MxWgO1XYRqo6jov8AWuMaLykO0dK6/wAfWkcd7Y2iAjLGbGS24klj+orBlsnP/LM49q65TV7HLSpuWpQhGYjntVe8wIcCtSK2dAwMTYJ7iqOowOMfuWVfYVMWkjtnFt3NXwtiC0LucAhpDj2BxWx5T+o/Ws7SrdRZRdg5RBz75P8AI1o/25Z/89v0qHqzK6RynxrsRpfieaUbkVoYrgBehdXCkk/QAfjXMvqyHxFpa+URGzvaE55YN90/+RB+Veq/tG6ITDp1wiDDiWBsgckgOOo4+4fT64zXjz2E+rada3kICsvkyK2ejBSrfqi12UHemjGekz0DTZYYRo9xGA8Vu7bSDjcrEHH47jVXyYVg0wjaGsb/AM3JPIXKHb+O1qwriwureO/hS6JjSZXiAxhU+bAH/fS/lXq2n/s3ePPE+jyalYWtq9pqRjvbZnuUUlGDEcZ44fvXQr9Bc0ep5rp1hL4f03yFlWX7Jqf2hG2/dyOnXr8lTa3Kwk1aKNkEQ1HzkXuPv9efTFeoy/sm/Eq5+2gWFkBMyyrm9T73OR1/2j+VTH9j/wCI8zXe6wssyxIQWvU5kypb/wBmqkpEc0SPw18LdO8caXqt/Lc3EMGpXnmqIto2hC2DyDz8zV0WofALRtVXU1mvb5Tf7WkMbIMEdxlTz16+tesfD34IeJvD3hPTtPure2S4hjxIEnBXdknrXXwfCfW8DcLcf9tf/rVol3OZyd9D4IudPPhrxxeWiq8kem63bSB8jgb0BLc9D8oyB1xyM8/eenp/osWBkFRzXh3jL9jnx9rXifXdQs30ow313FcQh7tkI2f3gE+vHI719O2Pw91OK2jjf7PvVQCQ5wf0rzMXSnO3KrnTRkluc08Ksp4qzYwxruz+Haum/wCFeaiUx5lvnP8AfP8AhUifDrUw+4SW3/fZ/wAK8+OGrLXlZ0+1h3PJ/irF59tdsQMtagflGf6CvjPxcu6JAM7QwyAeM4r9DvFXwd1jXYLhIZbQGSAIC8jD5tpB/h96+f8AWP2JfHGoaZJEt5oXnmZJFZrmXhQrgj/Vd9w/Ku+FKoo/Cc3PHnvc+f8Aw0uNFg+rf+hGq/iRMpASMnLc/lX0do/7FHjazsYoZdT0JHUHOLiYjr/1yqDWP2JPHGoCJV1TQU2k/euJv6RVTpVH9k3VWFtz5Wuhjy6TAEZOK+mZ/wBg3xvMFxrXh9SP+m05/wDaVPT9grxmIira9oWSOzzH/wBpVKoVLbEutDufMFmpbWLNQOmSfwFegWSYgQ4zkFq9isv2CvFlvfRzv4g0YhARtXzT1/4AK6m1/Yx8QRRxrJr2mZUAHCSEH9BVewqW2JVamnqz5yn1C3jZ1Z9uGI5U/wCFVDq9nk5nQf73H86+yF/ZIsTHEGubcOFAdh5nzHuetR6n+x1p99ptxbxajFbzSIVWXY7bM98bua5vqVVvY9NZhRjFK/4HxxezrLp80kTq6hSNyEEdKufDKx+0a3u6LErPn0+Uj+ZFfW+sfsW6bqGmTW1rrQsp3xiX7O0gXkE/L5gzxkVy+pfsrj4S+G9Q1v8A4SI6o0aKhiFn5PDOoJzvb27VvTw1SndtHDicTCu4qLPnrxMzXXjaQdUt4CMe/wAoH/s1MdDg8V1fgrw7Z+I9V168uwz/AL4RIQxGMbmP/oS10lx4A0tehm6/38/0rlqXlI6MPJRp2PLSmAeaz9SBeMKvTNeqz+A9NReHn692H+FY2peDLCKItvmA7DcOv5Uo3RpKaeh5bNfXdqm0S4VOVGBxxWD9pb1Ndp4n0ODT7J5Udy7MFUMRXHeS/tXXBJq5587X0PoT48aWbrwZJOquWtpY5AY22kZYKxz/ALrNXgvhmcrpOpWqxoXBljjGRgMHV1UH1IJFfVHj7STrPhTVLMcNNbSIp9CVOP1r5K8LO76tcQjbuuWjdVblcOCpHb1A9se1GFfutFVFZpnSuJb8yp9mcG601YSCnKXMe07PZiI+nXmv0d8JaCug+G9J05cbbS0igHH91Av9K/PDwBp8Op+MPCsJgbyptUjs1Uvnbl0JD8fNw3HTGD14r9KoecDFelBHLNjo02/SrSqMVnXF/wCTuEURmYHbnO1A/GFJ9yw6A9/SgahOGkVbdGZJBGQJCf7p7KcfK3U459Ac1pYyNZBgdKtIelUNPvIr6NmjYFlO11zyp/w7g9wQe9XoxzTsFznfH3jf/hBdO0+5Fp9ta7vorPyw5TbuDHdnaem3pwOeorhb79o6KxlvkTQZLkW0i4miuMxPE2dku4L90kY/FfWvVNctry60a8j014odSaFxayzLuSOXadrEegOOxrh/7B+I5Dk6jo0anyR5KQYOApEiqxjIXnG3crdBnoQ2M1JPRnsYT6q6f72Kb821+jKlr8exe2eqzx6P5b2dl9rSGS4YSTfvVj4URn5ctw3U8YU84D+0FN52qxQ6BHcSWKghI7/cZcuBxiP+HlX/ALr7V5yWG/pOgeNmsLhNR1bT1u/tEbQTWMCqDCJGLo26M9VK4wOw9yW6doXxBihtjLq2m/aFlQynylZWj8s71AESkMZNp3ZxjHHB3L39rs6LYJN+7Hf+Z/5FHxj8crjwrqBto9Ls7pPtL2xZ9Q8poseXgyAphC29mAJ+4A3emD48TpocV9P4feGRb6WyuIfPJCbFjkLBtvIKOce4H4aukaR8R7a5tH1HU9Jv0RMXCKvlCVt+Aw/dEg7OvOCcAAdaaugfEg2bRtrmni4No67yFYfaCx2txCOMYyfYDaSCzHv9biUcEkouMdOvM/8AI5mf9ouQT2sH/CPywvcQiUSzuVijGAWZ228KvzAk4wUapo/jvez3Kr/ZFslq0gT7SbgEJ/pJhIbJAVgo3YJB5HFdfBo3jkacEfVrD7UbyKRnKbv9HCfPGP3Y5L98cAnnNVrLw148SxukudftJLprUpFMiBR5/mAq5HlcDaCDyc7uMbQSe/tdi5sDvyR/8Cf+Rh6L8V9a1bQn1GXS7W0zJbKsLsxZBJPLC27kAkGLIwcnPG44Bo33xX8TpbTXK2Fnbx2/2eSaKSIuyJN5WBu8xRuUPIW3bR8o6Dk9N/wiXj2Rp3Pie3gJaTyljiDKoLsyHBTjC7Vx7Z3djPdeEPF0klyE8RDY74iYYQohjK9NhG4NhvQknOMDN2nbqQng09offL/L+rl74deJdQ8WaA15qVktlcpM0JjRWUHCr8wzzgknHtiunKe1M0izubTSbKC8lW4u44USaVAQHcAbiM+pzT766SygZ3zgDoOtdMVpqfP1nGVRumrIMUhYLXxJ8Tf25fGnhD4ga3othoGiGysrgxRNdRzNKVwCCxEgGTnPArmT/wAFBPiAx40Lw4frbz//AB6jmRlys/QESYPNc/8AEXTf7Y8Ca9aLH50j2UpjUdS4UlPx3AV4x+y1+0Vrfxui8Qrr1jYWM+nNB5QsEdQyv5mSdzN0Kdq9/Eu9Sp5UjBHqKGrolPlZ+c/w68V22kRT29xGVW4uWJlUnjBCc+3FenykuF6uDyDmvPta+F+oaBrGo6fE8U8cV3JCGBOUUSEEkEfjxXc24S3hiiRiUjQIoJ5wBivm56SZ9HTSUEMujsBXBBrl9Zl3NsJ4HrXR3k6lm559ua5DVLrMr455qUDPP/HNz+8hgB+Xlz/L/GuT2r71u+KLj7VqsnogCisbbXXDRHDPc+vrqPzIXVumK+O9Ysn8P+M54owYzFLNCMrgKEfen14BP419kuMk18r/ABx08aV8RjKc+XNJDMSR/fXyz/6ASf8A61Y4Z2nY6aq0R3P7O+kjWvjPpMJQNFHeNqPA+7tikYfqUr7v1S5+x2LOpRGZkiVn3YBZlXPy8/xf/XHWvjr9jS0W/wDibd3TIrm10lySpz5bmVEUH32g19ovCtxC8bdGBBr2obannTd2cvdxSW6bdwCAGKW2MfmmVfLZyjgMQWIIGeGJBPzBsGdXngug00k+OYiZI2BOPMDEHGcHy1fC4Bwv94CtKHTpoAsF1Gbu3yf3kSAADKgAoMYyM7sA5w/3QQtS2tjJmE29lGwkjUziWPYpbcjBuTkEbnIG0nKYJXHNkDtO3/21EfMT/UOskceGA2mPAyAMBWMoAPPJ/DowM+1UtM0tNPh2iSSZz1eVyxwOgyew/M8kkkknTiTA560CPLPih+0Dpvwt8R2Whz6Dq+t311bfaVXTI0fapZlAO5gckq3btXDn9tzRFcqfBfiMEEggiAEfh5lQfHTxLdeE/jVZ31lt88aJFH86ggAzTZryW9kOt3k15cMDNO5kfCDqa+jwOXLEU1OcdH5/8A4cViqFKmkqn7y+qtpa29+57KP23NBQ5Pg3xJ/wFYD/ACkqWP8Abe0QjK+CPExz3EcP/wAcrw8acka7gcjv0FaOk38mnFhHl4zzsZ2VQf73ykc8V6Lyimvhi/vPOp4+DdpzsvQ9oT9tfS2H/IjeJB6fJD/8cp3/AA2npxGR4D8SgepWHH/odeWW/iW4yhKoPLGBh3zj3O7nv+ZqUeJrtmIBbcMjd5r5wRjHLfj9an+yV/I/vNfruGv/ABv/ACU9LP7atko/5EHxCR0y3lf/ABVSf8NoWxjLj4f6+VHfdFj2/i+teXt4runl3CIDAK58yTgZ4/i7c4+pqpd6vc3jBCzRxbdpSNjg8k8gnnrSjlUesH95Msdhkvdq3+R6lJ+2xFj938PtYY/7VxEv+NVG/bdmDYX4c6ifXN9GP/ZTXlscJdjgN+PFTR2YJywwPrWv9k0/5X95gsxp/wA57F4J/a+l8XeOdF8PXHgW80qPU7gWwvJL1XEbFSQSoQZ6Y617p4kj3WvHTmvkXTtZlu/iN4MvrpUke31GztgyoEypkEYJwOSA3U819oX9h9sg2gAfWvnsdh3hp8lrXXqenSrU6vvU5XXpY/K39pvQzpvxp1su3lJcrDODtzkeWFzj6oa84j04vC8iz/IrLGxKqDlunG/PbrX6P/FL9kLw18VvES6xq895DdrCLfNrPsUqCxGRg8/Ma8xk/Yk+FNvP5cnii5V95j8s3y7twOCMY6ggivLVk/eR3RUqitBa/ecF+wyZNN+JHiLTzMGV9P3ugxjekqjjBIPDnnNfdMPQV5T8Ef2cfBPw0mfX/C1xcX73cDW/2qW58xCocFgAOPvIPyr2E2u08Vp6HO007S3Pmj4v2U1h471HZp8ssVxsmV0+6cqM9v7wNcG5mA2jS58f7v8A9avoL4waaqahYXSrzJE0een3Tn/2b9K84ayDfN2x0JxXzlePLVkj6GhLmpxaPN5/MfI/s646dCnFYF1aq4JOnXH4RV65cWqt0GT68H9KzZ9OAVsx9zyTWNzW54DrPhWO9dnjtLuKQ9xDkfjXP/8ACF3v/POX/vw1fRMumKTnaD7EVV/spP7grRSaM3CLNqO8WVQw5BrwL9pvTv32m3ajPmQyQswBzlSrJ+uevpXqFhqjKdhzgVx3x5RdQ8FrKpXdb3CPgjPDZT/2cVNJ2mgmrxPS/wBhuwd7bxTqskcf7/7LFG6R7SAFdip9fvIc+9fV0IxXzt+w1pzWvwRS5dCjXV/M3I6hAsQ/9FkV9GxDOK+iha2p5MtyeKraqDioIhj8KtRjg1TViLirED0qeOMelEaAGp0WpFc+Vf2g4jdfFx17RaXbr+ckx/qK4S30xVJyMj06V6V8XbVZvilrspkDMEt4wP7oEQOPzYmuXFrx0r9OyyNsHT9D89zKo3iZpdzl7uz2Z2rgE81RW2LSqpB25HWuxk08Nzt5Pamw+H5JZAUTGDk4UtXoyja93Y4KdR8ysrszJtOUNhcYA4KYwaiXT5ZGBDY9s107eH7tnIjVsdh5R/HvU0fh68XOFOW6ZjNZx5Ekub8UdmIqVa9WVX2Vr9EnZHMJpsu7qBg1P/ZpXAIyOtdSNAvcf8ezH3AP+FI+iXUa5kgZQOSSD/hVqdL+ZfecUoV3ryNfJnPLYcZxzTlsGY4K8V0FvpxL8jNWLmyECAlck9AB+tataHIqjbscs0Cafe6ZeMwSO1v7a5ZvRY5kc/otfccY3Kue47V8W+P5Tq2ja1cC2SCV7WTbFEm1QQmBx+AJ9TmvtGwmW7sbe4Q5SWNXBHcEZr4jPF79OT7M+xyeS5KkU72YjRjJ4rJufC2k3UzyzaVZSyNnLvboxOSSckj1JP4mtxl/OmOpFfM2ufSRnKHwuxnQ2EFlAsNvBHbxLnakSBVGTk8D3yaRkzkGrsiFqrsp7UWsS227s4D4t6eJ/DkFxt3Pb3AOQOQrAg/rtryBm+UhcqT2AyTX0B41sP7R8K6nD3EDSD/gPzf+y14C6CSLYzHBBBIOMivExsbVE+57ODleFuxWX5kG1dvOfl/iB71XuYcjB4478k1oZRVREKhQMBQMcVUuJ1JOWAI9Oa4DuM9rXCHgsAO9VvKX0NWZbhWJG7B7bqo+av8AdH/fVMDz/TFt76xgvrEsbSRQNrnLxN/db+h7geuQGeLfDjeJ/DN9YJtWWWEiNm6BxyhP/AgKpaA11pc37ma0WFhho3JO4cdccYrq4WjKvPbyweQMBhJNgoT0B46ehrK+t0Nq57h+zr4VuPB3wb8OaZeBRdpFJLKEORukkdzg/wDAq9NaaO1t5JppEhgiQvJLIwVUUcksTwAPU1neHrE6fodhbNgtFBGhIORkKAarXrzXLtcGKYwwSN5BhALo6kKXKEKx6upCsQVxjO/j6aGyueJJ+87GxHrVvkbFlceZ5PK+WS4LAqA5HPyEj1BBGQQa0LPUoLqQRBjHMd2IpBtY7dobjuAWAyCRnuetcJd69c2OovJHBJGXmZmDPmNpFR41IQsrbWIA29CYmwvIdt6wtVvLVYkt38tFbyS0zxiPO0+aXJ3s7AswYDIO8Fs8nZog7BBjip415qhokss+nxtMMTKWjc7Su5lYqSAVXgkZ6Y54yME6iITWYHzD4/tWufij4tZlP/HxAAPYWsP/ANeqEemkoMIxr1DxF4Lv7nxhrl6mnzzR3M6MriM4IESLwfTIpIfAWp5wNOm49UxX6hl9ajDC005Jad0fm2YU60sVUag7X7HnEGkFmIZMHtWpaWD2pYogO4Y5Fegw+ANU6/2e4PvgVZj+Huq7wTZPgdeR/jXdOthakXCck0/M82nHGUaiqUoyTWzscFCsked0aH04P+NTyWa3ZV5YELL0xkY/Wu9fwBqW75NObA9WH+NWU+Ht/g4tXX2LLn+dcPssrXSJ6X1/OntKf4nBrLKBxGuPoajuhNMjRlFIIwcCvQx8PL/bj7KST/tL/jSD4caiDkWbf9/F/wAaahlkXdKN/kRLGZzJOMpTs/U8uj0cpkiMmifQ/tC8mRT/ALBxXqn/AAr3Uz/y6f8Aj6j+tO/4V5qZI/0MD38xf8a7HjMM9HUX3o8uOExd7qnL7n/keJ33hsLaTI7SMrIwIJzkEc19CfCG+fU/hT4PupDull0e0Zz/ALXkrn9c1hTfC+/uUIaBV4/vr1/Otr4NeFtV8IfDjTNH1iPyryzkuIwvmK+IvPk8rlSR/qyn06V8rnlSjVjB0pJ2vsfWZJCtTc1Vi1e26Ow25pGX8anCY7U1xgHPHrXyh9SVJBg1XkGBkCrcgUHk4z0z3qGQfLxyD3qWyrNboz76zjvrKe2mUPDOjRSKe6kYI/I1+Set6HqGi6rdWM3nJLbSvCw84jDKxB7+oNfrowyK+Pfi/wCE9bsviNrwtLpDbSXBnjPlZwJAHxnd23EV5WOlGlBTkduFjKpJxR8gNPq2MJeXmB2W6b/Gqct7rIUkXd7+Fy/+NfTA0zxPEP8Aj6TZ0x5J/wAajl0jWw+fOQZ5P7o9fzrx/rVLuel7Coj5gF1rKAEzXwb1Ezf403+0dX/5/L3/AL/t/jX0peaRrDKR56pk/eWPn9arfYtZ/wCekf8A36/+vVLE0n1F7CocClxKU2iRsAYABxXQ+AzcXHjHRrMOzre3cVrJG43K6O6qwYHqMHv6VgG3bHynB9a9E+AFkNV+LPh2CRQwjmafB7GNGcH81FedSblUiu7PfqpRhKXZH22I8DGMfQVh2tlFCTYzQxrJvl8qcwM5V3kEqOuQwwDyW3cME4GQB0/ljriopbKOaSJzuWSM5V0YqR7ZHUdODwcDjivuFY+LOH1Dw+TKp+yIMBna2hjL8hGeRFdpYw6nzGRcrgfMCNvA2LfRLaIyQfZrZ5Xm8xFuoFlS7VySxTcQQ+wzggEAGR2KkMAdi08PC2MZju5UeMttZIoVYBtpcfc/iZS5Ixkse2ANTStIs9LTbawLFhBGCOSEBJVB6KNxwOgBwOKpiuXNJshZWcUPy7hlnKKFBYksxwB3JJ/GtBBk1DEMGrEYNFhXJFGRzVhSABUSjIqRRjrStoBNG248cVYwcZFV4YyKtqvpStYBUUt9K4Xxlrvirw/cObY6O8MjMbeOWGeSQoNuSwjyRjJyQu0ZGSOM92VIU7RzWLPoWqy6vHqVhqSWVysTwH7REZkKMVJwoZcNlRg59eK8rMZ4qnh5SwUFKotk3ZP1Z7GV/V/bP6wk15kfg+bXb23e41gaeYpY4pLaTT2LK4KZckkkEZ+7jt9eOi2+1VdJ0ldC0y0sInaSK3iWJGc5YhQAM+/FXkUkV6dK7gufc8/GezdWTpr3ehHt+tLg+9PK4NGK1OEjIJpjIDUx60wjk0EtkXlcV4f+0RN4W+HOh3HjDXtO1XVRd3UFq1vp8i5DFSAQGIGCFwec88V7uBkc14/+1f4bu/EfwQ1mPTrC41PUbaa1ure1tImlkdlnQHCqCThSx/CiS0OvCTlGqlGXLfRvyPmK2/ay+G731jZjwXrckTzqDPd3iq0QJjDNkZJx5anBPY+tfaunaXBo+nxWlqhS3jGEUknA9MnmvgL412Gs+MNDstN0r4LPoElnKC97peh3iyTgDadxYEEHrwK++vDs0174c0ua4V0uJLWJ5EkUqysUBIIPQ5PSsKLck20e5nuH+qVI0o1vaJq+6dn6ptfiSsu2vl/9qGwubLxnYX8FxdQRXdkFPlTMoZ0Yg8A9lKV9QSHsa8O/al0xLjw3o9+Qd0F00GQOgdNxP/kMfnXHmkObCya6ankZfJRxEb9T5mF1fm1kkGo3hAYLtM7ZOcn19qof2pfHzNt7ebQOv2hjWtJa+bAsWflySdvBbOOv5frVO4j8k7TwPTFfBOo1sfYcsexQW7v5HBkvrwAdMzHmpPttx/z+3H/f40k2edo56VX8p/RapVZdx+yi+hzazDHrXsv7J2li6+Jc1ywz9msJXDehZkX+RNeFRTlgDjtX0L+yjr+j6DqGvXOq6jaaezJFFCbmZYywJYtjJ56LXs4ON68bmGLdqMj618vjrSiPFc+PiN4TK5PifSP/AANj/wAaB8SvCHfxPpH/AIGx/wCNfXprufI2fY6NRg8VZjODXJ/8LL8Ig/8AIyaY3+7cqf5GnL8UPCYP/Ixaf/3/AFrTmj3I5X2OyRsDNWY2riP+FseEFIU+ILLJ9HzU/wDwtjwhDgnxDYtn+5Ju/lS549w5Zdjt4ye/rVhU3H2rhk+L/g4ddfs/wY/4Vah+MPg1umvWzH/ZDH+Qo549w5Zdjuo49o5qdAPxrhx8YfCKjnWYyP8Arm//AMTR/wALo8Ig8asp+kb/AOFHPHuHK+x3WBUsfGa4FvjV4RUZ/tPd7LC+f5VEfjv4TjJxdTP/ALsLUc8F1Dll2PRutLjArzYfH7wqSMPdn6Q//Xpx+PfhrONl+fpCP/iqPaR7kOEux6KRzSFa86Hx78NgkGG/x2/dL/8AFVWuf2iPC1qwWWPUF3cj9yp/9mpOpFbsPZyeyPTCuKTGK8s/4aS8KZ+5fH6w/wD16hl/aT8KoeIr/J/6YjH86XtYdxeyn2PWNwprHg+9eQP+054aHAs78+/lr/8AFVWk/ag0AD5dO1Bj6FUH/s1P29PuP2FTseuyIOcjmqzLg9MCvHpf2o9GLMP7Hvh/wNKqXH7UmlAfu9EvGI/vSoKSr0+4ewqdj2SWMfjXnfx10dtU+FuthFBlgVLhc9tjgn/x3dXJP+1PaKM/8I/Of+3lf/iayPEX7TVnrOh6hpzeHJNt3A8DbroYCspUn7voTXPiKtKVGUZS0aNqNKrGpGSjsz58FzIkfr7is+4vFMg3hmq1PMqxj5vm54rNuLg5G0da/Nkj7mwXN2oGVTA71S+1n+5U8pLxkFfm74qrtb/nkfzq1G+49jjI3JccYHtWlGC4ycdAelY0U7ADnj6VoW0jlRluvqK9RNp3Rk05aM0Y+MEEAjtU6ynOP5VltI/XPSrcT5RSQwJ9a9ajioSjabszzKuHlF+6tDXt3Kgd6vK3ANYsczlgo7VZS9GcFix9q3+s0f5kYqjU/lZtQy5x6VfibvnFYVvfxseEb8RV1NSSNAxjcKOvSsniaP8AMjX2NTsbcMhK+tamh3H+mbR1KniuXTWI0PAJz2q1pmtizu47h422DPHrSWKop/EDoVGvhPQlDMfuk1OkbnGFIxXL/wDCf26MB9kmI9iKlt/iVbyXEcK2Mrb2Cg7x1NbrGYd6cxzvDVl9k6qFfNZhvRAv3mkcKB+dTywmEqC8cikbleJw4I+ormxfTF2dUZSxycNilF/OTjYfxaujm1OVqx0QdUYHGMVbS7t3YBriKEngea2C3biuWF5MRzGT/wAC/wDrVYk8Zy6TbwobFZADt3M+D6+lKdWNKLnPZDjB1Gox3Z1i2pPXr7HNYfiSPyZYge6nH51nD4j3B5TT4yO/7w/4Vk6x4yuNSdN1rGhTONrE1wyzPCtWUvwO2GDrp3aL6YJ5onUbMDk1k/2ncLt2xpyO55pq3t255WMD8a5v7Qod39xt9Vqmhs5qOUAY5/KqDX0zPg7M/Q0NdShSW2cemaX9oUPP7h/VahYLL65pkwAUGqbyyGJpFC+nvmo4ruXyZjKSXCAx7QMZ3DOfwzR9fo+Yvq0yS6cRpzwfSqEL72nfO07CFDe5A/kSfwqI3LOSZCzEn0qKW4CAkg5968vE4x1naPwnbRoKmtdyrfKY1JOG7cUyK1EkQfbgDnk9aJ7iNnVm5GeAfWo7m8Zl2pzjvwePavPTZ1kcuZpWCc+nbFJ9lk9I/wA6iS4EOSyFT24p39oL6j8qsh3Wx59FCAgbOQPWtGJcIpUYqraHaTuUDHQCtFJB5edpOfWu9voSLblHwrKM59KtyIFA9ccCqMac7yCT6Vr6hAHstPlTcMo0bH/aDH+hFZ8t0U3ZpdyCNC4B5HfPSnpAWdRuAA4wRmoliZFIMhP1NSIjCQHdxjrWbVizRTGDtUFl46VaILRMOMkelU7bK7t3THygCrkMmF2468ZJ6VD0DYZaWREimQAjrmteO2VIWiCblzkAniq0M6gAn5sAAbqnt7o3R2Mp3e1TcTu9R8kKW0LncAHwpx16g/0qvbR/8Ta1KYWPzVYDv2qd7fdKqtxg54pVVBqkaoCEUoc+pzTUmmiejR6iungdFxQtgMnAzWrHHlc+1OSMBuK+3R8mzPXTsclRj6Vzni6IQxW4A5Zz29BXciMbcVyHjrKJZBCASXzn/gNcGYO2GmdmD/jxOSEbkHncxPA6Yq2LdYkDOTvx2qtCHSUZbI9cVaDAuckAEdSetfEn1L2JLecHnYVHTmobnzZZAi7kXtzmpodg+UnOe2KerLu+Z+AP4aaMmxbO3Cs/mHcrDGMc0raeSp5O3rzViKZHi+Q8jsaru7zjYCc9+auOhm22ypeAQQrhs7vToKwprkyPs3cDptOK6C/s9sSr1IGaz4tPihbzNik46k8imzSDSWpnvDkja7KQeRTZ4TLAwzlx2xk1JPMzy5HT+VRT3Lsp2rgAYOB3oQitb2aSr5aF3lI5UrwKRv8ARE8t8Kv94ircVyyJ8oG4856ZrPu2LkM/Lk8e1WlcLshkQzTZHKU77HD6R/lRLJ5EJKqSSOtZ/wBpf+635VqldEnKomJM56DvxVyCX5duBwciqcNxFLLt3r09f8+lXo4EI3GVcezCu137EJpbluIkY6c9q1YA13YCIAYSRnx9VyR/45WdF5G0ZkQfU1f0+6ghnjDOpQsAwBHQ8H9CahXTBu6K+0TMMYLdxjmpxGFjPy46Gi0eGI5LhpCOpqvPfDzSFVtvsDyayepaL9tCJMtI+3C8A9+R/ianmCRHbuye/PFZv2+NgQdxbHFPS8mETKFIyDg8VLQGrEFaPhjz+VWrR0jJyTx6CsWyuHMQVwx5yDg1dieRATztPHK1FimaXnea2cbQDximMC1zEQxwuOfU5JpYNvk7myfpwKmyjyI6r1x7VaIuezRuFjXvwKX7xOKghYNEpHoKcr8nBr7VbHyj3LK7gME1yXjmA3M1gAcBN5P/AI7/AIV1Qfg5Nc94mmWM24PJwx4HPavPzD/dpHXhHasmcwliqg8nIOOe1OEEss7IA20KCGOMN14H5fqKns5lZ2ZgNpOcEUzULkRMGjJJPBCjFfG2R9FdkMtuUYKGBP8As9jTTAdoy+W7jPSq1zfB3QpGPVj3qWS43ncvGR0oSK16l2DECFy4HHPeoUvTJIWXvxnHWo1k3jaRg/WljhwxDEZ7Yprckbe3UkrrGgxgYODUAXZktjn15qG7vGSUJjFQveBUk8z72PlPWmwtYWQRRs7KmSehJ4qtIV8oqUHtgVWLTXCjJAx3Bwak3osSqWJb0JyaYiIvlW4HHtVCWJsHnJ7Zq/8AaIojtHc4PPSqBd9xfJI6gE8Vol1HcZIJdhGVGKp4m/vLVmSVed5APf0qHzF/2f8AvqrsI5PWY/Dfh2WIXdtKJGXcDArMvBwed3qDUNhrnhTU7yK0t4pfPlOF83cg/E7sCtmO1/shZZYJ7t/M5YCQNjv0OaYNZlSXc0l6Mc52KT/KvqnCL+yeCpy3uWU8P6ZIwCwI/GcJcls/k1K3hS0YnFqyjt+9YH/0KrdrcSW9wLiO71CZn42TYwvA7DjqTWkFu70hml3N2yBWM6cY7G0ZtrUwW8OabA58yCRUAyT5r/41kWmpmKaWJ1CxI5A9QO1dV4lcWVrHFuzJLyef4R/+uvO55iuqyhjhXww/LH9Kzq0U6d7F0qrdSzZ1kMqTyjn5O1XmnPlhIx06t6VzNpcsowCAR3rTsblmYg42+ua8l0z01K5twXOyPg5I9atQ3ZyQAelZluyFjzz3q3GFDL15rnasXc0hIyQ5bIX2qW2bzSAQcgDAz06037H5kapk7R0q7YWvkzld3zHHb60ImT0PWbKTdbRNnqg/lU6kc8is6wkxZw8fwD+VWkfOa+1j8KPlJbss7uDzxXOeJnCXFux/uHp9a3u2KydZAFzBwG/d4+nJrz8w/wB3Z1YT+KjEjZW25XBI65qLYYpDIT0yOTxWmuAudoyPaqVxCGjyBnnOTXyjTse4mU54liXdwy1AZ9wKhCo/vAVblcsuOG9RUSBFwDtGe1QXewvzQDhQ+4ghse3/ANeqc0kkSSuw3BVJ+lXzMEHC59Cazb55WtZWfARjjGMCr6CT1MtLqRnG47ye5pz/ADqScNj8aBGd4IAVcdupqvctsdcE5HYVK1NBZw+wBV5PoP51SMMm4Bn5GckVqG6CxjcvPSs5p0eVstgegrRIm5C4jVskZI5yDUIUEfJnB4zUsgWR8BSQT2p7/LHtVNuPzqxXKr6fFMQWQs4HUnFR/wBmR/3P/HjU8JdEJ5PPUmm7x7002ibs8lvfHs9nqV7aXWmfv7aQwzFUJwRx1B6cU+z+Ktp5ag26DLYGVc5NclpkupeLxJqUzafJcTPmRpoOWOO+KZrNxd6PaxxPbabMm8uFjgBAbHJ/QV9p7OPY+e9o11PRofitbRRK22JEPRnV1U/iRiuns/Fr33hZ9chWGRIrxbXZG+QcoWzn8K+bx45lVQo03T+O/k1ah+JWoCEW3lRLblw5jUsFyM4OM47n86PYdkP2vdnrPi34gQ2gs7i8Us88giWKJvuqPvHn6/qKrXbh7uJxyrocZ9Oo/nXj/iDWpNcvLWRgAyKECL90c54/E/oK9b+xXU9raJbxmSRVXheuMYqatP8Ad2sTTnaomaMLqSBv6jmrttInTJOPeqI0HVYIlkktHw3HLLz+tTwabfj7tpIfxH+NeG6Ur7HtqpG25u2rrk/vME9s1pae7G7jBJbnAPpXKvYaqGyLK4wBklUzxXe/BrwfeeNdfmt7h5rC0hgMhn8rOW3AAAH8fyqVhZzdkhSxEIK7ZuQliV5A9SRVlQ6yqVwQOvFemQfAZJSAviCVB72in/2atCL9nZ5TlfEzD0BsAf8A2cVr/ZeI35fxOb69Q7nPWEmbG3Oedg/lV2OXdUN3pzaNcS2Dy+e1q7QGXbt37TjOMnGcetNhkwvrXvRTSSZ47ldtou78DrWfqkTNcQspB+XGO/U1MZckc4rufDvwa1rxno9vqtlqtlaQyblEU8LM2VYgnIPqK48ZRnXp8lNXZtQqxpT5pHBQ2ayKWcAEdFHBqrqFlGqs0LZXHcdDj/GvWz+zz4nB/wCQvpDemUlB/kayr/8AZ78XQqxXUNFkXuGeYf8AshrxHl+JtbkPQWKpXu5HhztI7sgbYAeSRxVfDZAZgSTwarapfppep31hc3VstxbSPDIocABlYg/qKzotaty5DTwtj0cV5rozTs0empJ7M6KW9RAFO0nHaqGsX/7uFcbgSW64/wA9ap/2pazjKXEO0dg4NZd3qkFxeskcyOEA6OCCTmqVN2tYE433L32skZyfzpnmoZOSQTVJZck5ZQPrTWJD8mo5bdDS6NCe5UqQOcCoFcuegx3JqvKMx7un0qOTUo44sAj0yx5q1FkOS2LEtxgYTHXnHWmwytMpBBXnqapxzBz95WY9Dmnfb2VPKYce3WqSZEnZaF64Xy0+RuvSqnz+tVpL3IIwQB0FV/tTej07Mm/c+b/DUxhDwMSDncB/Ot7V8SaXkcbDmuVR3t7gSpww4waszX1xPbmIHbGxywGea+5trc+bObkhbe20cU+KzlZlIQketa8Nlv8AbHrWjDarGBzn8KrmJsY9jaN/aFsCpOZVyPxFey27b79QCTtUArkjtXC6NaRNqVu7jAVs9O9eh6VEg3NIvzuCx56jtXNVndHTQheVx6Os8smXJPUDHU10FlaJHbDzGOCeFyDkVWsbNIyG8tc9iTnHtUup+fuRLYErnnbyK89tnqLWyMzV5pLCwmk85o45SUAQ8YHOD+le0fseaTs0XX9YfJa4uktlJ9EXcf1k/SvEvF5dILa2YYkWNSykDqwz/LFfVf7PmhLonwr0VCAktwrXT84++xK/+O7a7cKrzPOxckoadT12xfcRk8Vu2zHjDGudsxhRh0/OteIypHlNrnjgMM9a9uOx4rPH/F7bPEmpgD/l4c/mc/1rNR8A962PFEJn1+8kdWjZpNxVuo4FZsdsBnJJ+lee1dux1p6EIbLivpf4SO0XgLSwGwCJDjHrI1fN4tfn4NfQvw1m2eENNReQilT165J/rWlJNNmVR3SPQFmf+9n8KjmkYr82MVSinY06SUupBrqRgfDfxe0yfTPiF4jjDGHF80ysDgYfL/8As1cPl3AxOemMhq9b/aJt/J+JurI6qY7i3hnAPf5Qn/sprzrS7HTpY1jlt1Rz0cO2DXzNWPLUa8z6qi1yrToFuMwpIFEilQD6cf8A6qjMRilYzKGjJJBB59avXGnwWdrbqUZAxILHpnP1p89ra3LRNvLIcDCsRz0zjpUtkqN1cpRWcFxDnZGW46qD+fFUb1UlWXFvCrxHI3Rj5l//AF1uwaTAyyRxSuQvVQeM+uO1c/MAl0UkU5dmiyrgsAO+ByB05NK/cFBN6lFAkj/vIraIHn/Uj/CrsWk2cwVzBBICOMRjj1pkOmW8uULSIem4kc1be3SzhljEjgLg5zxUqVjSrTj2KE+jWyuy/ZYv+/a8inJ4etHXeLaEDjP7sc1o3UQaGGUbWLKRvGf88U7T0jVz5srKhx93r/8Aqq9WrnM4xXQ5m80a3Z5FgtowVbGNuCfSqP8AYh/59P51v3N4tvcNHLlgR94jsQfeoPsqf8/Lf99D/GnZC5UfO6Wd1KCwsFAwV3BVGc/hTH06VQUNkenQEVtX12EcKhx6jNU5JmkIAY7jXbzsn2UWUrOzktnWeKzKsG+U8HkVLc6VPe3T3E1i0ssrbmbdjJP0NX45vICqSGxycnvWhbXwwzFATgYyaHUaBUUzNsbH7I+BaeQf7xcn+tdDFIAgbzcnHPPT2qBJ4r2RE8rDsQtbFvpsSA7QOTgPmsJS5jqpwVMu2txHHYBPMO8DecHuarwX5adI1Y/vGC49ATiqYkUSSfMAoOAMcUy1YrcCbqsQLD2wOP1xXPu7HTqo3Ha3Mda1po7bL7pRHGAOuPlX+lfZOkWjaXp1pZxSuIreJIUAb+FQAP5V8m/Cu0TWPiJolsiHAuPPYkg8IC//ALLX2AkfHXNephY6NnhYx6xQ4XEw/wCW0n/fRp8dxM7qpmkIznliaTyhjvQgKS9OxrvueduUL9T9qkPX3P0qBOc5FX5I/MkZu+aFtCam2o+YphPmr3Tw5vt/CelFWZcwqflOOteMC2wfWvZ9NJj8O6an92CL/wBBFXBWbIk7mgL6VekrfnSHUZ/+ehqmzZPB4pjthT61ZB4F+0jJI3iaxndj++sivsSrMf8A2YV5JpsiiJmMu1xzx1r179puF/s2h3QUlVkkjYj/AGguP/QTXg8V/aWcjRSSsJCASNpxzXz2JVq0j6fBv9zE6W8vHfRZykih4mzyex7iuZTV7sc7zhu+Ov0q6mt2Qspo/PURuvlkspyMjrz9KxrSxinmCQXkcr4J4UjGPfFcjdzsikr8yOl0/UrsWJm3NhH8tmwMAnpmqc+oTXF27RKryKM8qucZxk8fSrCWRtrNzGUbjewA6n1rItrtvMmMbMqyDbhSAOxx+dNtomKUpNmiGY3LKh69unX1rQtJgwVJ5EXDeWFwemOvSuS+2OjyFptpViSz+mavwapBcf625QtjpuqEtbhL3o27E93fzec0Esax7TwNtSWOsSSSGFtiqw2hiuOfSop4I9TkmcXCRSxRE7WO4swxgHn0+tQ2iRblkY5jXlcED5vrzmtWpXJXs2nfcbqd55rKWAcdOag+0D/nmv8A3zT9YuEefb9nWNyAdqknnvWfuH90frTu07MUYqSujy+3jllTcQCfXYKaDsLh0jZkGThBwfwrQedbeMIi5IXrnrWfdxmJVEcZLN8zH+Q/z611XMNCJZycgxRsT0O2tCw8y8d90asAMn5cVnRwzkcxtk8YxW5psbQ2p8xSHdt2AO3vUtm3KrEi2SQt5uQCmDlBjBNWogwUMgD4Xgk1O52W6ApkOdxGOKntbZpnXaAg24PPX8KhuxSSepXfTmaMFYwx44GcmobuOKOCQImCDsYA5B/ziuquUKQbBG5IT7w4/Kub1S3/ALMhVWViGBfB9+B/KoW4PY9A/Zy0iO78aXt2kKbbS1I3LztZyAPxwHr6ZitmKjCk/QV5N+yZpKReG9Y1Nk+e5ulgGR/Cig5/OQ/lX0NbBQBgAH6V7uGhamvM+cxUr1Wl0MCHSJ5BxE5z7VZi8OXQlGLfcSOAzBe/ua6qCTpzV1JFI5AOPUV1chy3aMC2+Gv2pA7s8DsclVkBH8quRfCyNfvaiyexUGtuJogM+WmfXaKdJb2k4/eW0MhHd4wf6VSirCMY/C22Bz/aEhHoEHP41q27+WDYbHU24WNS38QHA/lU8UFpF9y3iT/dQD+lKVhDhvLXI5Bx0pNWEKbeQZGw1XlDrkFD9cVeFyMc4oNwuCcUgPFP2iLIXHgqGQgjyLxHJ9PlZf618v3VrbC4mLvIJlOTtPUflX2L8b7VdQ+HOsIw4URyZxkjDqa+O9ZWJLnDuqnYuGPGTx19K8LGL96fQ4Ft0rJ9Si0Vn5jI63IOdpywwf0rUsdFSPUVMEpIjIOT0P6VmoFdd2zc5z96uitQZbSCRZfLWRcNkdMDB/lXAkrXPRqSkluIt/8AZZJYXMhCAj92RjOcemT39KzFs1XzGHmls9SnT0q5dqljeiYF13AFcH5frzVvTpoprgjHmBWxgcZGDg/hVNpmUdFzXMWW2gZmjS4EhcFc7GG49cDPTvWcIrZWJFzuVRjb5eM966LXtNQmOS12RlW8zJz8x/yKwbhRaGYskR3AAArzgjOR/j9aNGNSd99x8bRStGi3XKZKfJg9uCfwrQ0t/I3qMyxg7s4xj171hRyxpslX535+TGMYrftozcP8sqwQSfMJGGBj6fj0FaRSIqu3Uj1C5t7xSB8jqcqwH55rP8uP/nqP++f/AK9Wru3SwlKLMJB146DPTn6Hn3qLYPSP/vqk1FsINpaM8shgnu7zcxZIySzHnAUdauoisxbkY6ijzC0C5b7zYAx29amjhIZegz1962ehUVdm9pduDtGxWGMnfxV6K1Es7SSwEQhsD5ePxqlZCOLTWuCd0h6Dviqn9qXLeZukYIBwM5H0rNtdS1F9DqWt4Vkz5bDaMnHQnFT2ixMu4RbU9z0rktMvbi4uFVpysa/M2T2q29/LHGSsjEHpk4BpNicHsP1LVLpb+VIZDsXACjJwe9M1q+ZQ8ZkLMPkyxyePy461YsrwyzJk/dG5z7AZ/pXN32+9nCjhmbg5xkk0Rdwl2a2PsP4GWJ0z4baKH5knRrgnGOHYsv8A46Vr0uCSuD8Paxo+k6XZWUepWZjtoVhXE69FAA7+1dFB4k01x8uoWzfSVT/Wvo6doxSPkajbm2dTFPxxVqObPOa5mDW7RsbbmE/SQVfh1WA4xKh+jVo5XIVzfjuCOanFwB3rFjvo2GQ4/MVMLtMffX86XNYo1hc8Gjz/AHrKW9UAncOO9OF2CRyKXMmNGmLjGT1prXy9B1rMe9Cg1CbxWPbNJsoq+PSLzwbrkWwSE2U2EPRiEJA/Ovi93jv0jma2iLE4I54AJ5HPuK+0LyZJbeaMnO9CpGeuRXxhq8kUagxxrD5cjIUXP+Psa8rGfEmetgpWjJeaNeygtLlWU2aI6KTuVz1HTvStKkdpCiKY0IIO5c859axLKdo5Uk27j0DbT36Vqy36vosszuHaNuVxjv8A5/OvOjroejUVndFy5tku7SLftYrxljjI/CmwQQ292ssZVXZQSXOen+QK5SHX2hLZjJjPX5quWutjUZlQrt2jKDJz9KVrbEtSavJG34pk+z2cclvE8ozifHCjjr349zXM3jwakVYw4MR8ohJMjuQQe/f8q19R1gz2phliPPD7Xx1Bx2+tY0H2bypYE3JKV3cnOWHOPyzTT7Bay2J4LCz8yLCuHcEj5s4OT149s1daGAWyeU2Bkghuo56VgrcHeGDbcHPXmte0vEmzCdo39GbnFUr3sVNaJli6sUurSN1+Z0GDg4qh/Zy/3W/MVHcamtq7pGWLKSvsaqf2zH/db8qq1jLmfmefCcSzlRnYo2gVqW0ZkwTyBRRWktzaltct6jIbaGK3zgYLHH5CqcUoKhCCwx0zRRXO9zqj8JsWECWqSkkGRsL06D0qpdSeZOQOFXJA7UUUpChuS2NwyQXhdjvaPYoHTJI/pmo7bTHm+cP8x6Ciim9IkS1kzqNPttQuG5ngReMloyf5GshNX1PzWH+i7c8ZRun50UVtzytucsKMJSaaL9rf6ncHEYttyjJ4YVa1DUtRsS3EDYxyGYdfwoope0mo3uHsKfPaxWtNd1Zihjtom3HAAmI/pUzeLdbhnaMW20qB0uiOoB9Peiikqs2nqTOhTUkki3B441xXRdkyn1F4fw7Vfn8da/bQwyFrxVkzjZeelFFJVZ66jVCndaBH8RtfC5a51D/wL/8Ar1ci8feIWjLedqII/wCnsH/2aiikq0+4ToQTVkKvxL14ytB9s1JW6ZM4x0/3q5ea4aezuSxLMZRISeTnkdfxooqeeU5JSLjTjBXQ+0vN1vgj3B9K1NMdp1uIcLIk6Zww+6cE5/Siihbl1NjmFQMzD7pPI9qs6WrWF7byBySHViQcHFFFLqhyfulvUlaFX8sAYPDE84PQGs+2YwywuwAYNzz1wRRRVPYxi20QTS+TcyoBnDEde3/6qmM/llSByOn09KKK0S1HvAj1VlMizKpRX6jOee9UPk96KK0cU9zBSdj/2QAA)](https://www.youtube.com/watch?v=a8evHU1CmSw "RRCMS")
